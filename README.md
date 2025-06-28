# CIFAR-10 Feed Forward Neural Network Classifier

This repository contains a simple **Feed Forward Neural Network (FFNN)** using TensorFlow and Keras to classify images from the CIFAR-10 dataset.

## 🤖 What is a Feed Forward Neural Network (FFNN)?

A **Feed Forward Neural Network (FFNN)** is the simplest type of artificial neural network where information moves in **one direction—from input nodes, through hidden nodes, to output nodes—without cycles or loops**. Each neuron in one layer is connected to every neuron in the next layer, allowing the network to learn complex patterns by adjusting the connection weights during training.

FFNNs are commonly used for:
- Image classification (basic cases)
- Regression tasks
- Simple pattern recognition tasks

They are easy to implement and understand, making them ideal for learning the fundamentals of neural networks, even though they may not perform as well as Convolutional Neural Networks (CNNs) on image data.

## 🚀 Features
- Loads CIFAR-10 dataset (32x32 color images in 10 classes).
- Normalizes image data for stable training.
- Uses a simple Feed Forward Neural Network with:
  - 3 hidden dense layers (1024, 512, 256 units with ReLU activation).
  - Output layer with softmax for multi-class classification.
- Trains for 10 epochs with validation monitoring.
- Plots training and validation accuracy/loss.
- Displays a test image with actual and predicted labels.

## 🗂️ Dataset
[CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) is a dataset of 60,000 32x32 color images in 10 classes:
- Aeroplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

## 🛠️ Dependencies
- Python 3.x
- TensorFlow
- Keras
- Matplotlib
- NumPy

Install dependencies using:
```bash
pip install tensorflow keras matplotlib numpy
