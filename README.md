# Decision-Tree-Classifier-for-Walmart-Store-Data
This Jupyter notebook builds a decision tree classifier to predict the Walmart store based on features like store size, temperature, promotions, etc. The model achieves 100% accuracy on the test set.
Problem Statement
Predict department-wide weekly sales for 45 Walmart stores located in different regions based on historical data. Holiday weeks are weighted 5x higher than non-holiday weeks.Approach
Exploratory Data Analysis on all data files.
Data
The data used is the 'walmart_cleaned.csv' file. It contains store data like:

1.Store - the store number
2.Size - the store's square footage
3.Temperature - the average temp that week
and more...
The target variable is 'Store', which represents the store number.

Model

The model built is a decision tree classifier from scikit-learn. The hyperparameters were tuned using GridSearchCV to find the best parameters.

The best parameters found were:

Criterion: gini
Max depth: None
Splitter: best
Using these parameters, the model achieves 100% accuracy on the test set.

Usage

The main steps are:

Import libraries and data
Explore and clean data
Split data into train and test sets
Build model with GridSearchCV to find best parameters
Evaluate model on test set
Visualize model as a tree plot
To use the model on new data:

Import the cleaned csv data
Select features to use for prediction
Instantiate model with best parameters
Call .predict(data) to generate predictions
