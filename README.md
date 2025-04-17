# Supervised_ML
This repository contains an implementation of Logistic Regression from scratch using Python and NumPy. It aims to build a classifier capable of solving binary classification problems using gradient-based optimization techniques. The project demonstrates various optimization methods, including Gradient Descent (GD), Stochastic Gradient Descent (SGD), and Mini-Batch Gradient Descent (MBGD).
Key Features:

Custom Logistic Regression Implementation: The model is implemented without relying on libraries like scikit-learn. It includes functions for training, prediction, and loss computation.
Multiple Optimizers: The project allows the use of different optimization techniques, such as:
Gradient Descent (GD): Updates the weights using the full dataset at once.
Stochastic Gradient Descent (SGD): Updates the weights one sample at a time.
Mini-Batch Gradient Descent (MBGD): Updates the weights using small batches of data.
Loss Function: The model uses binary cross-entropy (logistic loss) to measure the error between predicted probabilities and true labels.
Evaluation: After training, the model evaluates its performance using several classification metrics:
Confusion Matrix
Accuracy
Precision
Recall
F1 Score
Project Workflow:

Data Generation: Synthetic binary classification data is generated using make_classification from sklearn.datasets.
Data Splitting: The dataset is split into training and testing sets (80% training, 20% testing) using train_test_split.
Model Training: The logistic regression model is trained using the selected optimizer. The training process includes monitoring the loss at each epoch.
Model Evaluation: The trained model is evaluated on the test data using multiple classification metrics to assess performance.
