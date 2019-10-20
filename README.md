# SIGNS-classification

This project deals with applying convolutional neural nets on Image data to classify an image in to one of 6 categories.
It is part of Deep learning specialization in coursera but I extended that project to add some features to improve accuracy.

_Code is written in Tensorflow(did not make use of Keras)_

## Data

**SIGNS** dataset is a collection of 6 hand signs representing numbers from 0 to 5.

You can find sample of how data looks like in [here](https://github.com/raviteja-ganta/SIGNS-classification/tree/master/images)

Goal is to classify image in to 6 catgories.

* 1) 0
* 2) 1
* 3) 2
* 4) 3
* 5) 4
* 6) 5

We have two sets of data:

* Train data
* Test data

Train data is for traning Conv net. Test data(in this case used as validation data) is for selecting best model.
Data is included with this repo.

## Contents

Jupyter notebook has following contents in order to build model and also for selecting best hyperparameters.
* 1) Create placeholders
* 2) Intialize parameters
* 3) Forward propagation
* 4) Compute cost
* 5) Model creation
* 6) Solving bias problem
* 7) Solving variance/overfitting problem
* 8) Basic error analysis.
