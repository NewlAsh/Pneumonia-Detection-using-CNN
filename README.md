# Pneumonia Detection using CNN

A deep learning project that uses a **Convolutional Neural Network (CNN)** to classify chest X-ray images as **Pneumonia Positive** or **Negative**.

## Overview

The project demonstrates the basic workflow of image classification using CNNs:

* Image preprocessing and resizing
* Grayscale conversion
* Training and testing dataset preparation
* CNN-based feature extraction
* Binary classification using a sigmoid output
* Model evaluation and prediction

## Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* OpenCV
* Jupyter Notebook

## Dataset

The dataset consists of chest X-ray images divided into two classes:

* `Positive` — Pneumonia
* `Negative` — No Pneumonia

The images are split into training and testing sets before model training.

## CNN Architecture

The model uses multiple convolutional blocks:

```text
Input X-ray
    ↓
Conv2D (64 filters)
    ↓
ReLU
    ↓
MaxPooling
    ↓
Dropout
    ↓
Conv2D (128 filters)
    ↓
ReLU
    ↓
MaxPooling
    ↓
Dropout
    ↓
Conv2D (256 filters)
    ↓
ReLU
    ↓
MaxPooling
    ↓
Dropout
    ↓
Flatten
    ↓
Dense
    ↓
Sigmoid
    ↓
Positive / Negative
```
##THANKS

> **Note:** This project is for educational purposes and is not intended for medical diagnosis.
