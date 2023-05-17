# Credit Risk Modelling

# Introduction
In this project we use the dataset from a lending company in 2007-2014. You can look to the fully dataset in (https://www.kaggle.com/datasets/devanshi23/loan-data-2007-2014). There are 450.000+ rows and 75 columns in this dataset, with each rows represent 1 user or individu.
In this project we need to predict the credit risk from the dataset that contains many features about the borrowers, such as last payment, the purpose of borrowing, employeer title, etc.

# Outline of the Project Work
## Import Data
Importing data from csv file to process it using Jupyter Notebook.

## Explore the Data
- Looking the data types
- Columns details
- Null numbers
- Unique values

## Define Target
In this project we use target from a column in the dataset which is `loan_status`. We divide the target into `good_loan` and `bad_loan`.

## Pre Processing
- **Data cleaning**
  Including data leakage, missing values, small unique values.
- **Feature Engineering**
  Modify features from object to numeric, from datetime to numeric.

## Exploratory Data Analysis
- Data target distribution
- Statistical Descriptive
- Univariate Analysis
- Multivariate Analysis

## Feature Scaling and Transformation
- Feature Transforming
  One hot encoding, feature mapping.
- Standardization

## Model Training and Prediction
- Split data
- Check imbalanced data
- Modelling data
- Hyperparameter tuning

## Conclusion and Suggestion
