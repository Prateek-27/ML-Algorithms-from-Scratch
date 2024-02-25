# Machine Learning from Scratch

Welcome to the "Machine Learning from Scratch" repository, where we dive deep into the fundamentals of machine learning by implementing core algorithms using pure Python. This project aims to provide a hands-on approach to understanding the mechanics behind some of the most fundamental machine learning algorithms by building them from the ground up and comparing their performance with `scikit-learn` implementations.

## Overview

This repository contains detailed implementations of the following algorithms:

- **Simple Linear Regression**: Models the linear relationship between a single independent variable and a dependent variable.
- **Multiple Linear Regression**: Extends simple linear regression to accommodate multiple independent variables.
- **Binary Logistic Regression**: Used for binary classification tasks, predicting the probability that a given input belongs to a certain class.
- **Binary Logistic Regression with Regularization**: Improves the binary logistic regression model by adding L2 regularization to reduce overfitting.

Each algorithm is implemented from scratch in Python, with a focus on understanding the underlying mathematical principles. For each model, we also provide a comparison with `scikit-learn`'s implementation to validate our results.

## Contents

- `SimpleLinearRegression.ipynb`: Demonstrates the implementation of simple linear regression. Used the'Salary_dataset.csv' dataset to predicted salary given the years of experience.
- `MultipleLinearRegression.ipynb`: Contains the implementation and evaluation of multiple linear regression. Used the 'Student_Performance.csv' dataset to predict Performance Index given features like Hours Studied,	Previous Scores, to name afew. 
- `BinaryLogisticRegression.ipynb`: Showcases binary logistic regression implementation. Used the 'fake_bills.csv' to predict if the bill is genuine or not given features like diagonal,	height_left, to name afew.
- `BinaryLogisticRegressionWithRegularization.ipynb`: Implemented regularization to my binary logistic regression implementation. Used the 'fake_bills.csv'. 

## Implementation Highlights

- **Data Preprocessing**: Utilizes `StandardScaler` for feature scaling.
- **Model Training**: Employs gradient descent for parameter optimization.
- **Evaluation**: Compares custom implementations with `scikit-learn` models through metrics and plots.

## References 
- Supervised Machine Learning: Regression and Classification by DeepLearning.AI 
