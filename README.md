Rain Prediction in Australia — Machine Learning Project

Predicting whether it will rain tomorrow using 10 years of Australian weather observations.

This project uses Exploratory Data Analysis (EDA), data preprocessing, feature engineering, and multiple machine-learning models to build an accurate rain prediction system.

Overview

The goal of this project is to predict next-day rainfall (classification: RainTomorrow → Yes/No) using weather measurements collected across Australia.

The project includes:

✔ Data understanding
✔ Data cleaning (missing values, duplicates, outliers)
✔ Feature transformation & scaling
✔ Model training & evaluation
✔ Prediction visualization

 Dataset

Source: Kaggle
🔗 https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package

Rows: ~145,000
Columns: 23+

Key features used:

Temperature (min/max)

Rainfall

Humidity

Wind Speed

Wind Direction

Sunshine

Cloud Cover

Pressure

Location

Target Variable:
RainTomorrow → "Yes" or "No"

 Project Workflow
1️ Data Loading & Understanding

pandas, numpy

.head(), .info(), .describe()

Checking shape and feature types

2️ Exploratory Data Analysis (EDA)

Distribution plots

Correlation heatmap

Rainfall trend analysis

Outlier detection

3️ Data Preprocessing

Missing value handling

One-hot encoding for categorical columns

Label encoding target variable

Scaling numerical columns

4️ Model Building

You used multiple models such as:

Logistic Regression

Decision Tree

Random Forest

XGBoost / Gradient Boosting

KNN (optional)

5️ Model Evaluation

Metrics included:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

6️ Prediction

Predict next-day rain values

Compare Actual vs Predicted

 Data Preprocessing Steps

✔ Dropping duplicate entries
✔ Handling missing values:

Numerical → median

Categorical → mode

✔ Feature encoding:

OneHotEncoder

LabelEncoder

✔ Scaling:

StandardScaler / MinMaxScaler

 Models Trained
Model	Purpose
Logistic Regression	Baseline classifier
Decision Tree	Simple interpretable tree model
Random Forest	Best performing ensemble
Gradient Boosting / XGBoost	High performance boosting
 Evaluation Metrics

You calculated:

Accuracy Score

Confusion Matrix

Classification Report

ROC-AUC Curve (optional)

 Results

The best performing model was:
Random Forest / Gradient Boosting 

Achieved high accuracy and strong recall for rain prediction.
