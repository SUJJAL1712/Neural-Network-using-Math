# Neural-Network-using-Math

This notebook provides a step-by-step guide to building a neural network from the ground up, focusing on the mathematical principles underlying neural network operations. It is designed for educational purposes, offering insights into the data handling, model creation, training, and evaluation phases of neural network development, with a particular focus on handwritten digit recognition.

Features
Initialization: Introduction to the necessary Python libraries (numpy, pandas, matplotlib) and setup instructions for acquiring the MNIST dataset through Kaggle.

Dividing the Dataset: Demonstrates how to load and preprocess the MNIST dataset, including normalization and splitting into training and development (test) sets.

Model Architecture: Detailed explanation and implementation of a simple 2-layer neural network architecture, including the input layer, one hidden layer, and an output layer.

Forward Propagation: Walkthrough of the forward propagation process to predict outputs based on inputs through the network layers.

Cost Function: Introduction to the cost function used to evaluate the performance of the network.

Backpropagation: Explanation and coding of the backpropagation algorithm to compute gradients for the network parameters based on the error between predicted and actual values.

Parameter Update: Description of the gradient descent algorithm used to update the network parameters (weights and biases) to minimize the cost function.

Training the Model: Code to combine the previously described steps into a training loop that iterates over the dataset to learn the model parameters.

Testing on the Training Dataset: Instructions and code to test the trained model on sample images from the training dataset to visually inspect the model's predictions.

Checking the Accuracy on the Test Set: Evaluation of the model's performance on the development (test) set to quantify its accuracy.

Conclusion: Final notes on the model's achieved accuracy (~85%) on the development set, highlighting the effectiveness of the implemented neural network in recognizing handwritten digits.

Learning Outcomes

Understanding the basics of neural networks, including their architecture and how data flows through the network.
Gaining hands-on experience in implementing forward propagation, backpropagation, and gradient descent from scratch.
Learning how to preprocess datasets for neural network training and evaluate model performance.

Prerequisites

Basic knowledge of Python programming.
Familiarity with linear algebra, calculus, and the concept of gradient descent.
Understanding of the basics of machine learning and neural networks.

Tools and Libraries Used

Numpy for numerical computations.
Pandas for data manipulation.
Matplotlib for visualizing data and predictions.
Kaggle API for downloading the MNIST dataset.
