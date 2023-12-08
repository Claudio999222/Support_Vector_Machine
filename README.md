# Support Vector Machine (SVM) Demo

## Overview

This notebook serves as a practical demonstration of Support Vector Machines (SVMs), a powerful supervised machine learning algorithm used for classification and regression tasks. SVMs aim to find the optimal hyperplane that separates different classes in the feature space.

## Key Concepts:

1. **Support Vector Machines (SVMs)**: A versatile machine learning algorithm designed for both classification and regression. SVMs excel at finding the hyperplane that maximally separates classes in the feature space.

2. **Hyperplane**: In SVM, a hyperplane is a decision boundary that separates data points belonging to different classes. SVM seeks to find the hyperplane with the maximum margin between classes.

3. **Kernel Trick**: SVMs can efficiently handle non-linear decision boundaries by transforming input features into a higher-dimensional space using kernel functions.

4. **C-Support Vector Classification (C-SVC)**: SVM classification with a regularization parameter (C) that controls the trade-off between achieving a smooth decision boundary and classifying training points correctly.

## Application:

- **Classification Tasks**: SVMs are widely used for binary and multiclass classification problems.

- **Text and Image Classification**: SVMs find application in natural language processing for text classification and in computer vision for image classification.

- **Data Separation in High-dimensional Space**: SVMs are particularly effective in scenarios where the feature space is high-dimensional.

## Demonstration:

In this notebook, I apply SVM to the Titanic dataset from Kaggle to predict passenger survival. The demonstration includes the use of different kernels (linear, polynomial, radial basis function) to showcase SVM's flexibility in handling various data distributions.

The implementation covers key steps such as data preprocessing, model training, hyperparameter tuning, and evaluation. By comparing results across different kernels, we gain insights into how SVM adapts to different types of data.

This demonstration aims to provide a practical understanding of SVMs and their application in classification tasks, highlighting their robustness and versatility in handling complex datasets.
