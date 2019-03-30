
# learn-fastai
### - a personal repo to track my progress on learning fastai

## info
- associated with my GCP porject `rich-amphora-223523`, compute instance `my-fastai-instance`
- use the following to ssh into the gcloud compute instance and open up jupyter notebook port:
``` bash
gcloud compute ssh --zone=us-west2-b jupyter@my-fastai-instance -- -L 8080:localhost:8080
```
- on the instance, at `~/tutorials/fastai/course-v3` there are 2 git remotes:
  1. `remotes/origin`: this remote correspond to fastai's official git repo `https://github.com/fastai/course-v3.git`
  2. `remotes/xujiboy`: this remote correspond to this current git repo
