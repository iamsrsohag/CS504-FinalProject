# CS504-Final Project

This repository represents the project and tasks taught in the "CS 504: Adversarial Machine learning Course" offered at the University of Idaho. To know more visit the course page [CS504 - Adversarial Machine Learning](https://www.webpages.uidaho.edu/vakanski/Adversarial_Machine_Learning.html)


# Introduction

There are two notebooks. Each notebook will consist of 4 tasks. For both of the notebooks ResNet50 was applied as the backbone but it can be replaced with other model as described in the notebook.


## Notebook - 1
1. Train a deep learning model using transfer learning on the Fine-Grained Image Memorability FIGRIM data set.
2. Implement black-box evasion "Boundary" attacks againts the model we trained.
3. Implement a targeted boundary attack against the trained model.
4. Plot the adversarial image with the predicted label by the classifier.

### Dataset
In this notebook I've used the [FIGRIM](http://figrim.mit.edu/) dataset, consisting of 4,436 images of 11 scenes

## Notebook - 2 
1. Train a deep learning model using transfer learning on the Stanford Dog Breeds data set.
2. Implement White-Box PGD untargeted attack against our trained model
3. Implement a targeted PGD attack against the trained model in order to let Clairfai's Model predict wrong.
4. Use transferability attack. Where we will be considering Clarifai’s AI model as black box as we don't have the access to that.

### Dataset
In this notebook, I've used a subset of the Stanford Dogs dataset, consisting of 1,961 images of 12 dog breeds.

The tasks are divided into separate sections, each with detailed descriptions of the methods employed to execute them. The purpose of this notebook is to provide beginners with a guide to the techniques utilized in the adversarial machine learning domain. With the knowledge gained here, you should be able to implement other attacks or defenses.

### Requirments 
Please install the following. Make sure the versions are all up to date.

* Tensorflow 
* Numpy
* OpenCV
* Sklearn
* Matplotlib
* Natsort
* Adversarial Robustness Toolbox

Please note that "Adversarial Robustness Toolbox" can cause error in their latest version for some adversarial attack. But in this notebook I've used 1.13.1 and it worked without causing any issue.


