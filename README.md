# Semantic Segmentation with Scene Description

## Table of Contents
* [Semantic Segmentation](#semantic-segmentation)
* [Image Captioning](#image-captioning)
* [Video Segmentation](#video-segmentation)
* [Notes](#notes)

## Semantic Segmentation

### Dataset
Download the [Kitti semantic dataset](http://www.cvlibs.net/datasets/kitti/eval_semseg.php?benchmark=semantics2015). Extract the dataset in the `data` folder.  This will create the folder `data_semantics` with all the training and test images.


### Models 
#### 1. UNET
<p align="center">
   This is the general view of u-net architecture:  <br/>
   <img src="architectures/u-net-architecture.png" width="60%" height="60%">
</p>


#### 2. PSPNET
<p align="center">
   This is the general view of pspnet architecture:  <br/>
   <img src="architectures/pspnet-architecture.png" width="70%" height="70%">
</p>

#### 3. DEEPLAB
<p align="center">
   This is the general view of deeplab architecture:  <br/>
   <img src="architectures/deeplab-architecture.png" width="70%" height="70%">
</p>

### 

### Results 
<p align="center">
   <img src="Results/predictions.png" width="60%" height="60%">
</p>

<p align="center">
   <img src="Results/loss.png" width="100%" height="100%">
</p>
<p align="center">
   <img src="Results/jaccard.png" width="100%" height="100%">
</p>

## Image Captioning

## Video Segmentation


## Notes
* To replicate and run this code you just need to run it on google colab.
* Upload the dataset to your drive and make sure to change the directory in the notebook to the new one.
