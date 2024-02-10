# Wisconsin Diagnostic Breast Cancer - Logistic Regression Project

## Overview
This project focuses on using logistic regression to predict the diagnosis of breast cancer based on various features. The dataset used is the Wisconsin Diagnostic Breast Cancer dataset, containing 569 records with 357 benign cases and 212 malignant cases.

## Dataset Description
The dataset includes the following features:

* Mean, standard error, and worst (mean of three largest values) of the mean radius of the cell nuclei.
* Mean, standard error, and worst of the mean texture.
* Mean, standard error, and worst of the mean perimeter.
* Mean, standard error, and worst of the mean area.
* Mean, standard error, and worst of the mean smoothness.
* Mean, standard error, and worst of the mean compactness.
* Mean, standard error, and worst of the mean concavity.
* Mean, standard error, and worst of the mean concave points.
* Mean, standard error, and worst of the mean symmetry.
* Mean, standard error, and worst of the mean fractal dimension.

## Goal
The primary objective is to build a logistic regression model to predict whether a tumor is benign or malignant based on the provided features. This project aims to showcase the application of logistic regression in a medical context for breast cancer diagnosis.

## Implementation
Two implementations were developed for this project using the same features:

### Manual Logistic Regression:
Algorithm: Logistic regression was implemented manually using cross entropy loss function and gradient descent.
Accuracy: Achieved an accuracy of 95.78%.

### Scikit-Learn Logistic Regression:
Library: Logistic regression was implemented using scikit-learn libraries.
Accuracy: Achieved an accuracy of 97.37%.

Feel free to explore the Jupyter Notebook or Python script to gain insights into the logistic regression model's performance on breast cancer diagnosis.

