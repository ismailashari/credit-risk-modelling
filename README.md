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
- After doing hyperparameter tuning, we have better score for positive values. It means that we predicted better on the dataset. In the end we can predict with **94,2% accuracy** on the good loan or good borrowers.
- For the suggestion to get better score again, and to reduce the predicted bad loan that are actually good loan, we need to:
- **Data preprocessing.** Pay more attention to the data preprocessing, including how to fill the missing values, consider to take the outliers or not, etc.
- **Feature Selection.** This is important, because our model data is from selected features. Consider to make decision whether the feature is importance or not. Do more exploration on the data, and pay attention on the detail values. We can try to use Weight of Evidence (WoE) and Information Value (IV), to get more detail of the data.
- **Modeling.** Try more model algorithm, try more hyperparameter tuning, consider the scoring, etc.
