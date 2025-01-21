## MNIST Neural Network Project

This project implements a neural network using TensorFlow to classify the MNIST handwritten digits dataset. The notebook follows the instructions provided in the assignment, including data loading, preprocessing, model definition, training, and saving.

**Participants**

Sifa Kaveza Mwachoni

Marion Wandia Mwangi

## Project Overview

**Objective**

Build, compile, and train a neural network on the MNIST dataset.

Add at least one hidden layer with 128 neurons.

Save the trained model and use it to make predictions.

## Key Features

**Data Loading:**

Used the MNIST dataset, a collection of 28x28 grayscale images of handwritten digits.

The dataset contains 60,000 training samples and 10,000 test samples.

**Data Preprocessing:**

Flattened the images into 784-length vectors.

Normalized pixel values to the range [0, 1].

One-hot encoded the labels for multi-class classification.

**Model Architecture:**

Input Layer: 784 neurons (one for each pixel).

Hidden Layer: 128 neurons with ReLU activation.

Output Layer: 10 neurons (one for each digit) with Softmax activation.

**Model Training:**

Optimizer: adam.

Loss Function: Categorical Crossentropy.

Metrics: Accuracy.

Trained for 10 epochs with a batch size of 32 and 20% validation split.

**Model Saving and Prediction:**

Saved the trained model in .keras format.

Reloaded the model to demonstrate functionality.



