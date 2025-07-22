# Diamond-Price-Calculation-using-XG-Boost

## Overview

This project aims to predict the price of the diamonds based on the various characteristics of each of them as given in the dataset using XG Boost Regressor. 

## Dataset

The diamonds csv dataset, sourced from Kaggle, includes various characteristics such as the carat, cut, color, clarity and the length, width and depth of the diamond, all measured in millimeters.

## Requirements

- pandas
- numpy
- scikit-learn
- xgboost
- pickle

## Prediction Process

1. Start with downloading the diamonds dataset from the repository
2. Install the required libraries in Jupyter Notebook
3. Check for any inconsistencies, missing or null values and outliers in the data and fix them
4. Explore the data, uncover patterns and identify potential issues
6. Train the model and use the XG Boost Regressor to predict the diamond price
7. Evaluate model performance using Mean Squared Error(MSE).
8. Use Cross Validation to fit the best-performing model and save it as pickle file
