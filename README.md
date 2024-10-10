# Breast-Cancer-Classification-with-TensorFlow
This project demonstrates a machine learning model built using TensorFlow and Keras for classifying breast cancer as either malignant or benign. The dataset used is the Breast Cancer Wisconsin Dataset, which is available in the Scikit-learn library.

## Overview
Breast cancer is one of the most common cancers among women worldwide. Early detection and accurate classification between benign and malignant tumors play a critical role in effective treatment. This project uses a neural network model to classify tumors based on several input features extracted from cell nuclei present in breast cancer biopsies.

The model achieves an **accuracy of 96%** on the test data.

## Dataset
The dataset used in this project is the Breast Cancer Wisconsin dataset provided by Scikit-learn, which contains 30 input features computed from breast cancer digitized images of a biopsy.

Features: The dataset consists of 30 features such as mean radius, mean texture, mean perimeter, etc.

Target: The target variable indicates whether the tumor is:

0 = Malignant
1 = Benign

## Model Architecture
The neural network is a simple feed-forward model built using TensorFlow and Keras. The architecture includes:

Input layer with 30 features

A hidden layer with 20 neurons and ReLU activation

Output layer with 2 neurons and sigmoid activation

The model uses adam optimizer and sparse_categorical_crossentropy as the loss function.

