# Semantic-Image-Segmentation-on-CamVid-dataset

**In this project, I have used the FastAI framework for performing semantic image segmentation on the CamVid dataset.**

The Cambridge-driving Labeled Video Database (CamVid) is the first collection of videos with object class semantic labels, complete with metadata. The database provides ground truth labels that associate each pixel with one of 32 semantic classes.
More on this dataset can be found on their official website [here](http://mi.eng.cam.ac.uk/research/projects/VideoRec/CamVid/).

I'm going to be using [fastai datasets](https://course.fast.ai/datasets) for importing the CamVid dataset to my notebook.

We start by importing all the required packages for performing this semantic segmentation task. This includes the matplotlib package for data visualisation, and some fastai packages for performing the actual segmentation task.

```
# matplotlib 
%reload_ext autoreload
%autoreload 2
%matplotlib inline
```

```
# fastai packages
from fastai.vision import *
from fastai.callbacks.hooks import *
from fastai.utils.mem import *
```
