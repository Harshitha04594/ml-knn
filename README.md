Overview

This project implements the K-Nearest Neighbors (KNN) algorithm using the Iris dataset from Scikit-learn.
KNN is a non-parametric, instance-based learning algorithm that classifies a data point based on the majority class of its nearest neighbors.

📂 Dataset

Source: Iris dataset (from Scikit-learn)

Classes:

Setosa (0)

Versicolor (1)

Virginica (2)

Features:

Sepal Length

Sepal Width

Petal Length

Petal Width

🛠️ Implementation Steps

Import dataset from sklearn.datasets

Create DataFrame using pandas

Split dataset into train (80%) and test (20%) sets

Train a KNN Classifier (KNeighborsClassifier)

Tune hyperparameter k (number of neighbors)

Predict flower class on test data

Evaluate with Accuracy, Confusion Matrix, and Classification Report

📊 Results

Accuracy: ~96% (depending on k)

Confusion Matrix: Shows correct vs misclassified flowers

Best k-value: Typically between 3 and 7 for Iris dataset

Example Output:

Best K = 5
Accuracy: 0.9666
Confusion Matrix:
[[10  0  0]
 [ 0  9  2]
 [ 0  0  9]]

📌 Why KNN?

Simple and intuitive (majority vote)

Works well for small datasets

No training phase → computation happens during prediction

Sensitive to scaling → features should be normalized
