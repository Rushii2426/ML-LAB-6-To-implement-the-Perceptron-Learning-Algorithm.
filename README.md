# ML-LAB-6-To-implement-the-Perceptron-Learning-Algorithm.

## Theory
An Artificial Neural Network (ANN) is a supervised machine learning model inspired by the structure of the human brain. It consists of interconnected layers of neurons that learn patterns from data.

In this experiment, the **Seeds Dataset** is used to classify samples into three classes. The dataset is divided into training and testing sets, and the input features are standardized using StandardScaler.

A neural network with two hidden layers using ReLU activation and an output layer using Softmax activation is implemented. The model is trained using the Adam optimizer and sparse categorical cross-entropy loss. Early stopping is used to prevent unnecessary training.

The model is evaluated using accuracy, precision, recall, F1-score, and a confusion matrix.

## Objective
To implement an Artificial Neural Network for multiclass classification using the Seeds Dataset.

## Result
The ANN model is trained to classify seed samples into three classes and evaluated using standard classification metrics.
