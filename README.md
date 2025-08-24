# Fashion MNIST Image Classification

This project is a simple **image classification model** built on the [Fashion MNIST dataset](https://github.com/zalandoresearch/fashion-mnist), implemented using **TensorFlow/Keras**.  

It was developed as a **practice project** to explore neural networks and gain hands-on experience with training, evaluation, and visualization of deep learning models.

---

## Project Overview

- Dataset: Fashion MNIST (60,000 training images, 10,000 test images, 10 classes)
- Model: Fully Connected Neural Network (Dense layers)
- Input: 28x28 grayscale images of clothing items
- Output: One of 10 fashion categories  
  (`T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot`)

---

## Features

- Data preprocessing (normalization, train/validation split)
- Neural network architecture:
  - Flatten input (28x28 → 784 features)
  - Dense(300, ReLU)
  - Dense(100, ReLU)
  - Dense(10, Softmax)
- Training with **SGD optimizer** and **sparse categorical crossentropy**
- Visualization of training/validation curves
- Predictions with visualization of test images

---

## Model Performance

- **Validation Accuracy**: ~89%
- **Test Accuracy**: ~88%

---

## Sample Predictions

The model can predict clothing categories and visualize them:

