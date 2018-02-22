[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

# CarND-Traffic-Sign-Classifier-Project
---
In this project, traffic sign images from the [German Traffic Sign Dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset) which are fed into a deep neural network and convolutional network to classify the traffic sign images.

## Overview
* Load the [data](https://d17h27t6h515a5.cloudfront.net/topher/2017/February/5898cd6f_traffic-signs-data/traffic-signs-data.zip) set
* Explore and visualize the data set
* Design a deep learning model (tensorflow)
* Train, validate, and test the model
* Use model to make predictions on new images
* Analyze the softmax probabilities of the new images
* Summarize the results with a written report

## Motivation
The motivation of this project is to address one of the challenges of a fully autonomous car.  The autonomous system will require a means to identify signs and react properly.  This project only addresses identify signs.

## Installation
**Step 1:** Set up the [CarND Term1 Starter Kit](https://classroom.udacity.com/nanodegrees/nd013/parts/fbf77062-5703-404e-b60c-95b78b2f3f9e/modules/83ec35ee-1e02-48a5-bdb7-d244bd47c2dc/lessons/8c82408b-a217-4d09-b81d-1bda4c6380ef/concepts/4f1870e0-3849-43e4-b670-12e6f2d4b7a7) if you haven't already.

**Step 2:** Open [code](https://github.com/Eleven-/CarND-Traffic-Sign-Classifier-Project/blob/master/Traffic_Sign_Classifier.ipynb) in a Jupyter Notebook.  Jupyter Notebook is  using Anaconda

Jupyter is an Ipython notebook where you can run blocks of code and see results interactively.  All the code for this project is contained in a Jupyter notebook. To start Jupyter in your browser, use terminal to navigate to your project directory and then run the following command at the terminal prompt (be sure you've activated your Python 3 carnd-term1 environment as described in the [CarND Term1 Starter Kit](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/README.md) installation instructions!):

`> jupyter notebook`

A browser window will appear showing the contents of the current directory.  Click on the file called "Traffic_Sign_Classifier.ipynb".  Another browser window will appear displaying the notebook.  Follow the instructions in the notebook to complete the project. 

## Dataset and Repository
1. Download [traffic-signs-data](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset#Downloads). 
This is a pickled dataset in which we've already resized the images to 32x32. It contains a training, validation and test set.
•	The size of training set is 34799
•	The size of the validation set is 4410
•	The size of test set is 12630
•	The shape of a traffic sign image is (32, 32, 3)
•	The number of unique classes/labels in the data set is 43

## Deep Neural Network Model (LeNet)


## Tests
1. Test on the valid and test sets
2. Test on 5-6 images from the web


