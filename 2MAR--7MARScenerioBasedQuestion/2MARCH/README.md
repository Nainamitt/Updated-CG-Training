# Machine Learning Preprocessing and Model Evaluation

## Overview

This repository contains notes and examples related to important machine learning concepts used in data preprocessing and model evaluation. The topics include different encoding techniques for categorical data and methods for evaluating model performance.

---

# 1. Encoding Techniques

Encoding is the process of converting categorical data into numerical format so that machine learning algorithms can process it.

## Label Encoding

Label Encoding converts each category into a unique integer value.

Example:

Color | Encoded Value
Red   | 0
Blue  | 1
Green | 2

This method is useful when categories do not have a specific order but need to be converted into numbers.

---

## Ordinal Encoding

Ordinal Encoding is used when categorical values have a natural order or ranking.

Example:

Education Level | Encoded Value
High School     | 1
Bachelor's      | 2
Master's        | 3
PhD             | 4

This encoding preserves the order between categories.

---

## One-Hot Encoding

One-Hot Encoding converts each category into a separate binary column.

Example:

Color Column:

Red, Blue, Green

After Encoding:

Red | Blue | Green
1   | 0    | 0
0   | 1    | 0
0   | 0    | 1

This method avoids assigning numerical order to categories and is widely used in machine learning models.

---

# 2. Cross Validation

Cross Validation is a model evaluation technique used to test how well a machine learning model performs on unseen data.

The dataset is divided into multiple subsets called **folds**. The model is trained on some folds and tested on the remaining fold. This process repeats several times.

Example: **K-Fold Cross Validation**

If k = 5:

* Dataset is divided into 5 parts
* Model trains on 4 parts
* Tests on 1 part
* The process repeats 5 times

This helps reduce overfitting and provides a more reliable estimate of model performance.

---

# 3. Bias-Variance Tradeoff

The Bias-Variance Tradeoff explains the balance between two types of errors in machine learning models.

## Bias

Bias occurs when a model is too simple and cannot capture patterns in the data. This leads to **underfitting**.

Example:
Using a linear model for very complex data.

## Variance

Variance occurs when a model learns the training data too well, including noise. This leads to **overfitting**.

Example:
A very complex model that performs well on training data but poorly on new data.

## Tradeoff

The goal is to find a balance where the model is complex enough to capture patterns but simple enough to generalize well to new data.

---

# Technologies Used

* Python
* Scikit-learn
* Pandas
* NumPy

---

# Purpose of the Repository

The purpose of this repository is to understand key machine learning preprocessing techniques and model evaluation methods that help improve the performance and reliability of machine learning models.

