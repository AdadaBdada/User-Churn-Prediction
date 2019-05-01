# Sparkify User Churn Prediction

## Overview
[Medium Post](https://medium.com/@jinshuoada92/sparkify-user-churn-prediction-d4c3166ec675)

## What is churn Prediction?
Churn prediction is knowing which users are going to stop using your platform in the future. My project is Predicting Sparkify User Churn with Sparkify JSON Log File

## Objective and Background
The dataset is Sparky, which is a streaming service user log file similar to Spotify. The aim of the project is to build up a machine learning model to predict user churn (cancellation) using pyspark.

## Dependencies
* Python 3.5+
* pyspark.sql,
* pyspark.ml,
* datetime,
* Numpy,
* Pandas


## Methodology

- Define Target Variable (churn) and Exploratory Analysis
- Feature Engineering (Create New Feature and Transformation)
- Modeling (Random forest, logistic regression, SVM and gradient boosting tree)
- Evaluation (precision, recall, F1-score)


## Result
End of this project, two main iterations on a churn-prediction model were implemented and evaluated:

Model used a simple pivot of the event that seemed to contain the most relevant difference between churning.
Non-churning users.
Three models were trained with this data, given the following F1 Values:

- Gradient Boosted Trees - 68.9%
- Random Forest - 68.4%
- Support Vector Machine - 68.4%

## Improvement
- Feature Engineering: dive in deep about the data analysis to find the magic feature to help imporve the model performance
- Hyperparameter tune.
