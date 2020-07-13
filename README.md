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

After we prepare our data with the images and their labels, a sample batch of data looks something like this:

![data][lg]

[lg]: https://github.com/adityarc19/Semantic-Image-Segmentation-on-CamVid-dataset/blob/master/images/Screenshot%202020-07-14%20at%201.48.00%20AM.png

FastAI conveniently combines the images with thier labels giving us more accurate images for our training process. Thus the above sample batch contains all the transformations, normalisations and other specifications that are provided to the data.

### Model

We are going to be using a U-Net model, which is one of the most common architectures that are used for segmentation tasks. A U-Net architecture looks something like this: 

![unet][unet]

[unet]: https://github.com/adityarc19/Semantic-Image-Segmentation-on-CamVid-dataset/blob/master/images/Screenshot%202020-07-14%20at%202.00.36%20AM.png

More on this can be found [here](https://lmb.informatik.uni-freiburg.de/people/ronneber/u-net/).

Also, we're going to be using a pre-trained model called ResNet34 inside the U-Net architecture.






