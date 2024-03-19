#Face Mask Detection System

##Overview

The Face Mask Detection System is a cutting-edge application designed to enhance public health and safety measures by utilizing advanced machine learning and computer vision technologies. By leveraging TensorFlow, Keras, and OpenCV, this system is capable of accurately detecting the presence of face masks on individuals in real-time. The project aims to contribute to the ongoing efforts in managing public health, especially in settings where wearing a face mask is mandatory or recommended.

##Features

Real-Time Face Mask Detection: Utilizes a trained machine learning model to detect face masks on individuals in real-time with high accuracy.
Color-Coded Feedback: Provides immediate visual feedback; a green overlay indicates a mask is properly worn, while a red overlay signals the absence of a mask or incorrect wearing.
Advanced Machine Learning Model: Employs a sophisticated convolutional neural network (CNN) trained on a large dataset of images with and without face masks to ensure reliable detection.
Face Detection: Integrates OpenCV's face detection capabilities to first identify the presence of a face before assessing mask status.
Technology Stack

TensorFlow & Keras: Used for building and training the machine learning model.
OpenCV: Facilitates real-time video processing and face detection.
Python: The primary programming language for developing the application.
Dataset

The model is trained on a diverse dataset comprising thousands of images categorized into two classes: 'With Mask' and 'Without Mask'. This dataset ensures that the model can accurately identify the mask status under various conditions and across different face types.

##Getting Started

###Prerequisites
Python 3.6 or later
TensorFlow 2.x
Keras
OpenCV

###How It Works

####Face Detection: 
Upon starting, the application uses OpenCV to capture live video feed and detect faces in real-time.
####Mask Detection: 
For each detected face, the TensorFlow and Keras powered model predicts the presence of a mask, providing a probability score for accuracy.
####Visual Feedback: 
Depending on the prediction, the application overlays a green rectangle for faces with masks and a red rectangle for those without masks or improperly worn masks.

