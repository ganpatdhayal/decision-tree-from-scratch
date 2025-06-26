# Decision Tree Regression from Scratch

This project implements a **Decision Tree Regressor** from scratch in Python without using any machine learning libraries like scikit-learn. The goal is to understand the fundamentals of decision tree regression, including how trees are built recursively based on minimizing variance.

## 📌 Features

- Built using only NumPy and basic Python
- Supports recursive tree building based on variance reduction
- Predicts continuous target variables (regression)
- Handles stopping criteria like max depth and minimum samples
- Clear and educational code structure for learning purposes

## 🧠 What is Decision Tree Regression?

Decision Tree Regression is a supervised learning algorithm that predicts continuous values by learning decision rules inferred from the data features. It splits the dataset into smaller subsets while at the same time an associated decision tree is incrementally developed.

The goal at each node:
- Find the feature and threshold that splits the data into two groups such that the variance (MSE) is minimized.


