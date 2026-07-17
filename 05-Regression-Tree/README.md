
# Decision Tree Regression

## Overview

This project demonstrates the implementation of the **Decision Tree Regression** algorithm using Python and Scikit-learn.

Decision Tree Regression is a supervised machine learning algorithm used to predict **continuous numerical values**. It builds a tree-like model by recursively splitting the data into smaller subsets and predicts the average value of the target variable at each leaf node.

---

## Problem Statement

A real estate company wants to estimate the price of houses based on their characteristics. Instead of manually estimating the price of every property, the company wants to build a machine learning model that predicts house prices using historical housing data.

The prediction is based on the following features:

- Area (Square Feet)
- Number of Bedrooms
- House Age

The target variable is the **House Price**.

---

## Objective

Build a Decision Tree Regression model that predicts the price of a house based on its features.

---

## Dataset

A manually created sample dataset is used in this project.

### Features

- Area (Square Feet)
- Bedrooms
- Age of House

### Target

- House Price (Lakhs)

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
3. Select features and target variable
4. Split the dataset into training and testing sets
5. Train the Decision Tree Regression model
6. Predict house prices
7. Evaluate model performance
8. Predict the price of a new house
9. Visualize the Regression Tree

---

## Evaluation Metrics

The model is evaluated using:

- Mean Squared Error (MSE)
- R² Score

---

## Sample Prediction

### Input

- Area = 1700 sq.ft
- Bedrooms = 3
- House Age = 9 years

### Output

```
Predicted House Price: 64 Lakhs
```

---

## Decision Tree Visualization

The trained Regression Tree is visualized using Matplotlib, making it easier to understand how the model predicts house prices based on different conditions.

---

## Concepts Covered

- Supervised Learning
- Regression
- Decision Tree Regression
- Recursive Data Splitting
- Mean Squared Error (MSE)
- R² Score
- Model Evaluation
- Decision Tree Visualization

---

## Conclusion

This project demonstrates how Decision Tree Regression predicts continuous numerical values by learning decision rules from historical data. The model recursively splits the dataset into smaller groups and predicts the average target value at each leaf node.

---

## Future Improvements

- Use larger real-world datasets
- Perform Hyperparameter Tuning
- Compare with Linear Regression and Random Forest Regression
- Reduce overfitting using tree pruning

---

## Author

**Mubeen Sheikh**
