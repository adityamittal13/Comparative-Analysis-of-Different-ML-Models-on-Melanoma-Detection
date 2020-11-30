# Semi-Supervised-GANs-For-Melanoma-Detection

## Prerequisites

This liveProject is intended for intermediate Python programmers with at least some deep learning experience, preferably in image classification with convolutional
neural networks. Knowledge of PyTorch would be helpful, but is not required. No prior experience in generative modeling, including GANs, is assumed. 

### Tools

- Basics of PIL
- Basics of Matplotlib
- Intermediate Python
- Intermediate NumPy

### Techniques

- Classification as a machine learning task
- Intermediate deep learning concepts such as convolutional neural networks

## Python Libraries

- Torch 1.1.0: PyTorch, one of the most popular and fastest-growing deep learning frameworks
- Torchvision 0.3.0: PyTorch-based package for computer vision
- NumPy 1.15.4: a general-purpose mathematical package optimised for scientific computing
- Sklearn 0.20.1: for some basic data science utilities
- Matplotlib 3.0.2: for visualizing the data and the metrics
- Tensorflow 2.2.0: for building the semisupervised GAN framework

## Dataset

The dataset can be found at https://lp-prod-resources.s3.amazonaws.com/other/MelanomaDetection.zip. It contains the melanocytic nevus image dataset separated into three folders: labeled, unlabeled and test.
The images are a pre-processed subset of a dataset available through the Dataverse project. All images are color 32x32 pixel JPG files. 
The naming convention for images in the labeled and test folders is as follows: each filename ends with either *_0.jpg or *_1.jpg, corresponding to a melanoma-negative 
or melanoma-positive image respectively. The number of files is as follows:

- _Labeled:_ 200 (evenly split between melanoma positive and negative)
- _Test:_ 600 (also evenly split between melanoma positive and negative)
- _Unlabeled:_ 7018 (class distribution unknown)
