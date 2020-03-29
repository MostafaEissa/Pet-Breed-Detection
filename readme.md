# Overview

using a pretrained ResNet34 model for pet breed detection.  

# Dataset 

The [Oxford-IIIT Pet Dataset](http://www.robots.ox.ac.uk/~vgg/data/pets/) was released in 2012 which contains 37 category pet dataset with roughly 200 images for each class (12 cat breeds and 25 dogs breeds.) The dataset is about 750MB in size.


Note: the dataset was not  uploaded in this repository.

# Model

A pretrained ResNet34 model on imagenet.

The model was fine tuned using [scikit-learn](https://scikit-learn.org/) and [PyTorch](http://pytorch.org/).

# Metrics

The model achieved 90% accuracy on the validation set (random 20% subset of the training dataset).