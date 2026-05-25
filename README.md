
# Animal Image Classification using CNN

## Project Overview
This project implements an image classification model using a Convolutional Neural Network (CNN) to classify animal images into 10 different categories. The model is trained using TensorFlow and images from the Animals-10 dataset.

The goal of this project is to build a deep learning model capable of recognizing different types of animals from images and export the trained model into multiple deployment formats.

---

## Dataset

Dataset used: Animals-10 Image Dataset

The dataset contains images from 10 animal classes:
- Dog
- Cat
- Horse
- Elephant
- Butterfly
- Chicken
- Cow
- Sheep
- Spider
- Squirrel

Dataset source:
https://www.kaggle.com/datasets/alessiocorrado99/animals10

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- OpenCV
- Scikit-learn
- Matplotlib
- TensorFlow.js

---

## Model Architecture

The CNN architecture used in this project includes:

- Convolutional Layers (Conv2D)
- Batch Normalization
- Max Pooling
- Dropout
- Fully Connected Layers (Dense)
- Flatten Layer

Training optimization techniques used:

- Data Augmentation
- EarlyStopping
- ReduceLROnPlateau

---

## Model Performance

Training Results:

Train Accuracy : 90.23%
Train Loss     : 0.25

Test Results:

Test Accuracy  : 86.54%
Test Loss      : 0.34

These results show that the model generalizes well between training and testing data.

---

## Project Structure

project/
│
├── dataset/
├── notebook.ipynb
├── saved_model/
├── tfjs_model/
├── tflite/
├── requirements.txt
└── README.md

---

## Installation

Install the required dependencies:

pip install -r requirements.txt

---

## Running the Project

Open and run the notebook:

notebook.ipynb

Steps performed in the notebook:
1. Load dataset
2. Image preprocessing
3. Data augmentation
4. CNN model training
5. Model evaluation
6. Export trained model

---

## Model Export

The trained model is exported into several formats:

SavedModel  
Used for TensorFlow deployment.

TensorFlow Lite (.tflite)  
Used for mobile and embedded applications.

TensorFlow.js  
Used for web-based applications.

---

## Requirements

Libraries used in this project:

tensorflow
numpy
opencv-python
scikit-learn
matplotlib
tensorflowjs

Install them using:

pip install -r requirements.txt

---

