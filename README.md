## Basic overview
 This is the repository for the paper "Effects of label noise on performance of remote sensing and deep learning-based water body segmentation models" . 
 This repository contains:
 - [Dataset](https://github.com/monsurhillas007/LabelNoisePerformanceonWaterBodySegmentation/tree/main/Dataset)
 - [Notebook containing the model](https://github.com/monsurhillas007/LabelNoisePerformanceonWaterBodySegmentation/blob/main/model.ipynb)
 
### Dataset
The [dataset](https://github.com/monsurhillas007/LabelNoisePerformanceonWaterBodySegmentation/tree/main/Dataset) contains total 110 georeferenced clipped tiff files of Dhaka city collected using the GEE  and also correspondent binary labels. They have been used for training, validating and Testing the model. 

### Notebook
The [notebook](https://github.com/monsurhillas007/LabelNoisePerformanceonWaterBodySegmentation/blob/main/model.ipynb) contains the original model which have several sections containing data loader, data visualization, data augmentation, loss function, u-net model with encoder weights, and test function.

### Requirements for the model
 1. pytorch
 2. skimage
 3. numpy
 4. opencv
 5. PIL
 6. segmentation_models_pytorch

### Getting the repository

This repository can be downloaded and also cloned by the following steps, you can try either.
[git](https://git-scm.com/) repository:

    git clone https://github.com/monsurhillas007/LabelNoisePerformanceonWaterBodySegmentation.git

or [download a zip archive](https://github.com/monsurhillas007/LabelNoisePerformanceonWaterBodySegmentation/archive/refs/heads/main.zip).

### Getting started with the code

After downloading or cloning the repository seperate your downloaded dataset in three individual folders such as Train,Valid,Test. seperate both image files and label files.

Before we run the code we create an ['anaconda'](https://www.anaconda.com/) environment and install all the requirments on that virtual environment.



To create the environment:

    conda create --name YOURENVNAME

After we create the virtual environment we must activate it:

	conda activate YOURENVNAME

The code given in the repository is a notebook file which contains multiple cells working as individual python fie. to open the notebook type this in your anaconda prompt:

	jupyter notebook

When jupyter notebook is open, adjust the necessary paths according to your needs and run the notbook.

#### Data augmentation
In this notebok, the labels of the dataset can be augmented in various ways. Different kind of augmentation functions are commented there. we can use those augmentation according to our need.