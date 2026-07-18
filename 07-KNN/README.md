
# K-Nearest Neighbors (KNN)

## Overview

This project demonstrates the implementation of the **K-Nearest Neighbors (KNN)** algorithm using Python and Scikit-learn.

K-Nearest Neighbors is a supervised machine learning algorithm used for both **classification** and **regression**. It predicts the output of a new data point by finding the **K nearest neighbors** in the training dataset. For classification, the majority class among the neighbors is selected, while for regression, the average (or median) of the neighbors' values is used.

---

## Problem Statement

A school wants to predict whether a student will **Pass** or **Fail** based on their academic performance.

The prediction is made using the following features:

- Study Hours
- Attendance (%)
- Assignment Score

The target variable is:

- Result (Pass / Fail)

---

## Objective

Develop a K-Nearest Neighbors model that predicts whether a student will pass or fail based on their study habits and academic performance.

---

## Dataset

A manually created sample dataset is used in this project.

### Features

- Study Hours
- Attendance
- Assignment Score

### Target

- Result (Pass / Fail)

---

## Technologies Used

- Python
- Pandas
- Scikit-learn

---

## Workflow

1. Import required libraries
2. Create the dataset
3. Encode target values
4. Select features and target
5. Scale features using StandardScaler
6. Split the dataset into training and testing sets
7. Train the KNN classifier
8. Make predictions
9. Evaluate model performance
10. Predict the result for a new student

---

## Feature Scaling

KNN is a **distance-based algorithm**. Features such as attendance and assignment scores have different ranges, so feature scaling is required.

StandardScaler is used to standardize all features before training the model.

---

## Choosing K

The value of **K** determines how many nearest neighbors are considered when making a prediction.

- Small K → May cause Overfitting
- Large K → May cause Underfitting

The optimal value of K can be found by testing different values and comparing model accuracy.

---

## Evaluation Metrics

The model is evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

---

## Sample Prediction

### Input

- Study Hours = 4.5
- Attendance = 78%
- Assignment Score = 68

### Output

```
Pass
```

---

## Concepts Covered

- Supervised Learning
- Classification
- K-Nearest Neighbors
- Majority Voting
- Distance-Based Learning
- Feature Scaling
- Model Evaluation

---

## Advantages

- Easy to understand and implement
- No training phase required
- Works well with small datasets
- Can be used for both classification and regression

---

## Limitations

- Slow on large datasets
- Sensitive to irrelevant features
- Requires feature scaling
- Choosing the correct value of K is important

---

## Conclusion

This project demonstrates how K-Nearest Neighbors predicts the class of a new data point by examining the closest training examples. It is one of the simplest and most intuitive supervised machine learning algorithms.

---

## Future Improvements

- Compare different values of K
- Visualize nearest neighbors
- Use a real-world dataset
- Compare performance with Logistic Regression, Decision Trees, and SVM

---

## Author

**Mubeen Sheikh**
