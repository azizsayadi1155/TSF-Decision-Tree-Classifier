# The Sparks Foundation - Iris Species Classification using Decision Tree

## Project Overview

This project implements a Decision Tree Classifier to predict the species of iris flowers based on their sepal and petal measurements. Using the famous Iris dataset, I demonstrate the entire machine learning pipeline from data loading and preprocessing to model training, evaluation, and prediction.

## Data Description

The Iris dataset contains 150 samples with the following features:
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

The target variable is the Iris species:
- Setosa
- Versicolor
- Virginica

## Methodology

1. Data Collection: I loaded the iris dataset from a CSV file using pandas.
2. Data Preprocessing: I checked for missing values, removed the 'id' column, and split the data into features (X) and target (y). Then, I further split the data into training and testing sets.
3. Data Visualization: I created a pairplot to visualize relationships between features and a correlation heatmap to show the strength of correlations between variables.
4. Model Building: I created a DecisionTreeClassifier and trained it on the training data.
5. Model Evaluation: I made predictions on the test set and evaluated the model's performance using accuracy score, classification report, and confusion matrix.
6. Model Visualization: I visualized the decision tree to understand how it makes decisions.
7. Making Predictions: I created a function to make predictions on new data and demonstrated its use with an example.

## Results

The Decision Tree Classifier achieved an accuracy of 100% on the test set. Detailed performance metrics, including precision, recall, and F1-score for each species, are provided in the notebook.
