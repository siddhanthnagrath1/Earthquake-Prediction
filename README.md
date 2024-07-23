# Earthquake-Prediction
# Machine Learning Model for Earthquake Magnitude Prediction
This repository contains a machine learning model built with Keras to predict earthquake magnitudes based on geographical coordinates, depth, and date/time features.

# Table of Contents

 * Introduction

* Features

* Installation

* Usage




* Evaluation

 * Prediction

* Achieved Accuracy

# Introduction
Earthquake prediction is a critical task in seismology and disaster management. This project aims to predict earthquake magnitudes using historical earthquake data. The model is built using a neural network implemented in Keras with TensorFlow backend.

# Features
Predict earthquake magnitudes based on:
 * Latitude
* Longitude
* Depth
* Date and time of occurrence
# Installation
To run this project locally, follow these steps:

Clone the repository:


1.git clone https://github.com/siddhanthnagrath1/Earthquake-Prediction.git

cd Earthquake-Prediction


2.Install the required dependencies:


!pip install -r requirements.txt


Ensure you have Python 3.6 or later installed along with pip.

# Usage
Training the Model
To train the earthquake magnitude prediction model:


python train_model.py
This script will preprocess the data, train the neural network model using Keras, and save the trained model (earthquake_model.h5) to disk.

# Evaluation
To evaluate the model on test data:


python evaluate_model.py


This script will load the trained model and evaluate its performance on the test dataset, displaying metrics such as mean squared error and accuracy.

# Prediction
To make predictions with the trained model:


python predict.py --latitude 37.7749 --longitude -122.4194 --depth 10 --date "01/09/1965"


Replace latitude, longitude, depth, and date with the specific values you want to predict. The output will be the predicted earthquake magnitude.

# Achieved Accuracy


The trained model achieved an accuracy of 97% on the test dataset.
