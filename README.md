# Medical-Imaging-and-AI-Detecting-COVID-19-in-Radiographs
Overview
This project aims to develop a deep learning model for classifying COVID-19 images into different categories using a Convolutional Neural Network (CNN). The dataset used includes various COVID-19-related images, and the model's performance is evaluated using training and validation datasets. The primary goal is to achieve high accuracy in classifying the images correctly, which can aid in automated diagnosis and analysis.

Dataset
Source: The dataset is a publicly available COVID-19 image dataset containing various categories of images. (You may want to provide a link or description if possible)
Categories: The dataset includes labeled images categorized into three classes:
Class 0: Normal
Class 1: COVID-19
Class 2: Viral Pneumonia
Model Architecture
Model: The model used is a custom-designed CNN based on AlexNet or ResNet18, configured with three output classes for classification.
Layers: The CNN architecture consists of multiple convolutional layers, max-pooling layers, fully connected layers, and a final softmax activation layer for classification.
Training Process
The training process involves iterating over multiple epochs to adjust the model's weights and minimize the loss function. Here are some key aspects of the training process:

Epochs: The model is trained for 30 epochs to ensure adequate learning.
Batch Size: The training and validation sets are divided into 7 batches per epoch for iterative learning.
Optimizer: Adam optimizer is used with a learning rate (specify if used).
Loss Function: Cross-entropy loss function is used to measure the difference between the predicted and actual class labels.
