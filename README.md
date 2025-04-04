# DeveloperHub-DataScience-Internship
Task 3 Fraud Detection System

About Dataset

Please click on the link given below to download the dataset

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

# Credit Card Fraud Detection

This project aims to detect fraudulent credit card transactions using machine learning techniques. It leverages a real-world dataset and implements two popular classification models: Logistic Regression and Random Forest.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models](#models)
- [Evaluation](#evaluation)


## Introduction

Credit card fraud is a significant problem for financial institutions and consumers alike. This project demonstrates how machine learning can be used to identify potentially fraudulent transactions. The project includes data preprocessing, model training, evaluation, and a prediction function for practical use.

## Dataset

The project utilizes the "Credit Card Fraud Detection" dataset from Kaggle. This dataset contains credit card transactions made by European cardholders in September 2013. It includes features such as transaction amount, time, and a class label indicating whether the transaction was fraudulent (1) or legitimate (0).

The dataset exhibits a significant class imbalance, with a much higher proportion of legitimate transactions compared to fraudulent ones. This imbalance is addressed through undersampling the majority class during the preprocessing stage.

## Models

Two machine learning models are implemented in this project:

**1. Logistic Regression:**

- A simple and widely used linear model for binary classification.
- Efficient for datasets with a large number of features.
- Provides interpretable results by assigning weights to each feature.

**2. Random Forest:**

- An ensemble learning method that combines multiple decision trees.
- Robust to overfitting and capable of handling complex relationships in the data.
- Achieves high accuracy and generalizes well to unseen data.

## Evaluation

The performance of both models is evaluated using the following metrics:

- **Accuracy:** The proportion of correctly classified transactions (both fraudulent and legitimate).
- **Precision:** The proportion of correctly identified fraudulent transactions out of all transactions predicted as fraudulent.
- **Recall:** The proportion of correctly identified fraudulent transactions out of all actual fraudulent transactions.
- **F1-Score:** The harmonic mean of precision and recall, providing a balanced measure of performance.

The results are visualized using bar charts to compare the training and testing accuracy of both models.
