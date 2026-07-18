
# Support Vector Machine (SVM)

## Overview

This project demonstrates the implementation of the **Support Vector Machine (SVM)** algorithm using Python and Scikit-learn.

Support Vector Machine is a supervised machine learning algorithm used for both **classification** and **regression** tasks. It works by finding the optimal decision boundary (hyperplane) that maximizes the margin between different classes, resulting in better generalization for unseen data.

---

## Problem Statement

A bank wants to automate its loan approval process by predicting whether a customer's loan application should be approved based on their financial information.

The prediction is made using the following features:

- Age
- Annual Income
- Credit Score

The target variable is **Loan Approval Status** (Yes / No).

---

## Objective

Develop a Support Vector Machine model that predicts whether a customer's loan application should be approved based on their financial profile.

---

## Dataset

A manually created sample dataset is used in this project.

### Features

- Age
- Annual Income
- Credit Score

### Target

- Loan Approved (Yes / No)

---

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib

---

## Workflow

1. Import required libraries
2. Create the dataset
3. Encode target values
4. Select features and target
5. Scale the features using StandardScaler
6. Split the dataset into training and testing sets
7. Train the Support Vector Machine model
8. Make predictions
9. Evaluate model performance
10. Predict loan approval for a new customer

---

## Feature Scaling

Support Vector Machine is a distance-based algorithm. Therefore, feature scaling is performed using **StandardScaler** so that all input features contribute equally during training.

---

## Kernel Used

The implementation uses the **Linear Kernel** because the sample dataset is linearly separable.

```python
SVC(kernel="linear")
```

---

## Evaluation Metrics

The model is evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

---

## Sample Prediction

### Input

- Age = 31
- Annual Income = ₹48,000
- Credit Score = 690

### Output

```
Loan Approved
```

---

## Concepts Covered

- Supervised Learning
- Binary Classification
- Hyperplane
- Margin
- Support Vectors
- Linear Kernel
- Feature Scaling
- Model Evaluation

---

## Advantages

- Effective in high-dimensional data
- Works well for linear and non-linear classification
- Robust against overfitting with proper parameter selection
- Can use different kernel functions

---

## Limitations

- Computationally expensive for very large datasets
- Sensitive to noisy and overlapping data
- Choosing the correct kernel and parameters requires experimentation

---

## Conclusion

This project demonstrates how Support Vector Machine can accurately classify data by finding the optimal decision boundary with the maximum margin between classes. SVM is widely used in applications such as spam detection, image classification, handwriting recognition, and fraud detection.

---

## Future Improvements

- Compare different kernel functions (Linear, Polynomial, RBF, Sigmoid)
- Perform Hyperparameter Tuning
- Train on larger real-world datasets
- Compare performance with Decision Tree and Logistic Regression

---

## Author

**Mubeen Sheikh**
