# Titanic - Machine Learning from Disaster

A beginner machine learning project based on the Kaggle Titanic dataset.

## Objective

Predict whether a passenger survived the Titanic disaster using passenger information.

## Model

- Logistic Regression

## Features Used

- Pclass
- Sex
- Age
- SibSp
- Parch
- Fare
- Embarked

## Data Processing

- Handled missing Age and Fare values using median imputation
- Handled missing Embarked values
- Encoded Sex as binary values
- Applied one-hot encoding to Embarked
- Dropped Cabin because of a large number of missing values

## Results

- Validation Accuracy: 81.01%
- Kaggle Score: 76.32%

## ML Workflow

Data Loading → Exploratory Data Analysis → Data Cleaning → Feature Engineering → Train/Test Split → Model Training → Evaluation → Kaggle Submission
