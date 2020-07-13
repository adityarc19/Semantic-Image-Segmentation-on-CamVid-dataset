# Semantic-Image-Segmentation-on-CamVid-dataset

**In this project, I have used the FastAI framework for performing semantic image segmentation on the CamVid dataset.**

The Cambridge-driving Labeled Video Database (CamVid) is the first collection of videos with object class semantic labels, complete with metadata. The database provides ground truth labels that associate each pixel with one of 32 semantic classes.
More on this dataset can be found on their official website [here](http://mi.eng.cam.ac.uk/research/projects/VideoRec/CamVid/).

I have used [fastai datasets](https://course.fast.ai/datasets) for importing the CamVid dataset to my notebook.

Required installation for this project:

```
 pip install http://download.pytorch.org/whl/cpu/torch-1.0.0-cp36-cp36m-linux_x86_64.whl
 pip install fastai
```
More info on installation procedures can be found [here](https://docs.fast.ai/install.html).

### How our data looks

A sample image data:

![sample image][logo]

[logo]: https://github.com/adityarc19/Semantic-Image-Segmentation-on-CamVid-dataset/blob/master/images/Screenshot%202020-07-14%20at%201.32.40%20AM.png

We also get a labelled dataset. The labelled counterpart of the above image is :

![label][l]

[l]: https://github.com/adityarc19/Semantic-Image-Segmentation-on-CamVid-dataset/blob/master/images/Screenshot%202020-07-14%20at%201.41.49%20AM.png
