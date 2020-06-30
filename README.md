# Self-Driving-Car

- This repository demonstrates a real world case study.The aim of this project is to create a model to predict the correct steering angle from the given test image of the road.

- iam building a minimal version of self driving car. Here, i have a front camera view. This will transfer input to the computer. 

- Then Deep Learning algorithm in computer predicts the steering angle to avoid all sorts of collisions. 

- Predicting steering angle can be thought of as a regression problem. 

- We will feed images to Convolutional Neural Network and the label will be the steering angle in that image.

- Model will learn the steering angle from the as per the turns in the image and will finally predicts steering angle for unknown images.


![Final_short](https://github.com/RameshBattu/Self-Driving-Car/blob/master/selfdriving%20car%20run%20dataset%20visual-gif.gif)

You can download and watch full video from here: https://drive.google.com/file/d/1OJeIUGg4APbgjRdEPmqi5JLF-y9TsBTH/view?usp=sharing
<hr>

# Dataset

Refer to: https://github.com/SullyChen/Autopilot-TensorFlow

There are total 45406 images in the dataset along with their steering angles. We will split the dataset into train and test in a ratio of 70:30 sequentially.

# Objective

- Our objective is to predict the correct steering angle from the given test image of the road. Here, our loss is Mean Squared Error(MSE). Our goal is to reduce the MSE error as low as possible.

# Prerequisites
we have installed following softwares and libraries in our machine before running this project.

Python 3: https://www.python.org/downloads/

Anaconda: It will install ipython notebook and most of the libraries which are needed like pandas, matplotlib, numpy and scipy: https://www.anaconda.com/download/

* Libraries:

Tensorflow: It is a deep learning library.
pip install tensorflow

OpenCV: It is used for processing images.
pip install opencv-python

**<nav style="text-align:center">
<a href="https://www.linkedin.com/in/rameshbattuai/">RAMESH BATTU</a></nav>**
