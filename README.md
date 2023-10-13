# DecisionTree-Classifier on Housing Dataset

## Overview
This repository contains a Jupyter Notebook demonstrating how to use Decision Tree Regression to model the Housing Dataset. Decision tree regression is a machine learning technique used for modeling and predicting numerical values. In this example, we'll use a Decision Tree Regressor to predict housing prices based on various features.

## Getting Started
1) Import necessary libraries:
> Pandas for data manipulation
> NumPy for numerical operations
> Matplotlib for data visualization
> Scikit-learn for machine learning tools

2) Load the Housing Dataset:
> The dataset is loaded from a CSV file.
> The data contains features such as crime rate (CRIM), average number of rooms (RM), and more, with the target variable being the median house value (MEDV).

3)Data Preprocessing:
> Split the data into features (X) and the target variable (y).
> Split the dataset into training and testing sets.
> Scale the data using StandardScaler to ensure that all features have the same scale.

4) Create a Decision Tree Regressor:
> Initialize a Decision Tree Regressor model.
> Fit the model to the training data.
> Make predictions on the testing data.

5)Evaluate the Model:
> Calculate various regression metrics, including Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) score.
> Interpret these metrics to assess the model's performance.

6)Hyperparameter Tuning:
> Perform hyperparameter tuning using Grid Search CV and Randomized Search CV.
> Find the best hyperparameters for the Decision Tree Regressor.
> Create a new regressor with the best hyperparameters and evaluate its performance.

7)Plot the Decision Tree:
> Visualize the Decision Tree model for better readability.
> Adjust the figure size as needed.

8) Feature Importance:
> Obtain the feature importances from the trained Decision Tree model.
> Display feature importances in a bar chart for better understanding.
