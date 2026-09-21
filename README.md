# MNIST Digit Classification

## Deep Learning Assignment

This project implements handwritten digit classification using the MNIST dataset and TensorFlow/Keras.

## Objective

The objective is to build a neural network capable of classifying handwritten digits from 0 to 9.

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Jupyter Notebook

## Dataset

The MNIST dataset contains:

* 60,000 training images
* 10,000 testing images
* Image size: 28 × 28 pixels
* 10 classes: digits 0–9

## Model

The original neural network consists of:

* Flatten layer
* Dense layer with 128 neurons and ReLU
* Dense layer with 64 neurons and ReLU
* Dense output layer with 10 neurons and Softmax

## Experiment

Dropout layers with a rate of 0.2 were added to the network as an experiment. The original and modified models were evaluated and compared using test accuracy.

## Files

* `MNIST_Deep_Learning_Assignment.ipynb` – Jupyter Notebook
* `MNIST_Assignment_Report.pdf` – Assignment report
* `images/` – Graphs and prediction results

## Result

The model successfully classified handwritten digits from 0 to 9. The exact test accuracy and experimental accuracy are reported in the notebook based on the actual training run.
