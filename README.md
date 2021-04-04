# LabelNoisePerformanceonWaterBodySegmentation
 This is the repository for the paper "Effects of label noise on performance of remote sensing and deep learning-based water body segmentation models" . 
 This repository contains:
 - Dataset
 - Notebook containing the model
 
### Dataset
The [dataset](https://github.com/monsurhillas007/LabelNoisePerformanceonWaterBodySegmentation/tree/main/Dataset) contains total 110 georeferenced clipped tiff files of Dhaka city collected using the GEE  and also correspondent binary labels. They have been used for training, validating and Testing the model. 

### Notebook
The notebook contains the original model which have several sections containing data loader, data visualization, data augmentation, loss function, u-net model with encoder weights, and test function.

### Requirements for the model
 1. skimage
 2. numpy
 3. opencv
 4. PIL
 5. segmentation_models_pytorch

