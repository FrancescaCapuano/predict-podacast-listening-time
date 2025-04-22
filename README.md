# Predict Podcast Listening Time

This repository contains my solution for the **Kaggle Playground Series - Season 5, Episode 4** competition: **Predict Podcast Listening Time**. The goal of this competition is to predict the listening time (in minutes) of podcast episodes based on various features.

## Overview

The dataset provided for this competition is synthetically generated and consists of different podcast and user-related features. The challenge is to build a machine learning model that can accurately predict the `Listening_Time_minutes` for each podcast episode in the test set.

## Approach

In this project, I use a variety of machine learning techniques to predict the listening time for each podcast episode. The steps I followed include:

1. **Exploratory Data Analysis (EDA)**:
   - Visualizing and understanding the distribution of the features.
   - Identifying correlations and relationships between features and the target variable (`Listening_Time_minutes`).

2. **Data Preprocessing**:
   - Cleaning the dataset and handling missing or null values.
   - Scaling and transforming features as necessary to improve model performance.

3. **Modeling**:
   - Trying different regression models, including:
     - Linear Regression
     - Random Forest Regressor
     - XGBoost Regressor
   - Hyperparameter tuning using cross-validation to find the best model.

4. **Model Evaluation**:
   - Evaluating the models based on the **Root Mean Squared Error (RMSE)** metric.
   - Comparing different model performances and selecting the best one.

5. **Final Submission**:
   - Generating predictions on the test set and preparing them for submission in the required format.
