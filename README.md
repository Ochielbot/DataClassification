# DataClassification

Synthetic Data Classification using Decision Trees
This repository contains a simple synthetic dataset with 1500 instances designed for a binary classification problem. Class 1 is generated with three Gaussian distributions, and Class 0 has a uniform distribution. The goal is to demonstrate the use of a Decision Tree classifier to classify the instances.

Dataset Generation
The dataset is generated using NumPy and Matplotlib in Python. Three Gaussian distributions with means [6,14], [10,6], and [14,14] are used for Class 1. Class 0 is generated with a uniform distribution over the range [0, 20].


Decision Tree Classification
A Decision Tree classifier is implemented using the scikit-learn library. The dataset is split into training and testing sets, and the classifier is trained on the training set. The accuracy of the classifier is then evaluated on the test set.

