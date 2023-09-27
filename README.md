# Decision-Tree-Classifier-for-Walmart-Store-Data

This Jupyter notebook provides a decision tree classifier to predict Walmart store locations based on features such as store size, temperature, promotions, and more. The model achieves 100% accuracy on the test set.

## Problem Statement

The goal of this project is to predict the Walmart store location (Store number) based on historical data. Weekly sales for 45 Walmart stores, located in different regions, are predicted. Holiday weeks are given a higher weight (5x) than non-holiday weeks.

## Approach

The approach for this project involves the following steps:

1. Exploratory Data Analysis on all data files.
2. Building a Decision Tree Classifier to predict store locations.
3. Tuning hyperparameters using GridSearchCV to find the best model configuration.

## Data

https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting

The data used for this project is contained in the 'walmart_cleaned.csv' file, which includes store data such as:

- Store: Store number
- Size: Store's square footage
- Temperature: Average temperature for the week
- and more...

The target variable to predict is 'Store', representing the store number.

## Model

A Decision Tree Classifier from scikit-learn is used for this project. The hyperparameters of the model are tuned using


