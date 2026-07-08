# Forest Cover Type Classification using LightGBM

This project builds a high-performance machine learning model to predict **forest cover types** using the **Forest Cover Type** dataset. The workflow includes data exploration, feature engineering, model training, hyperparameter tuning, and performance evaluation.

## Features

* Exploratory Data Analysis (EDA)
* Feature engineering based on terrain and hydrology
* Stratified train-test split
* Baseline LightGBM model
* Hyperparameter tuning with cross-validation
* Performance evaluation using Accuracy, Precision, Recall, and F1-Score
* Confusion matrix and feature importance visualization
* Comparison with Random Forest classifier

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* LightGBM

## Results

The tuned **LightGBM** model achieved higher accuracy and better macro and micro F1-scores than the baseline model and outperformed the Random Forest classifier while requiring less training time. Feature importance analysis identified **Elevation** and **Hydrological Distance** as the most influential predictors.

## Project Workflow

1. Load and explore the dataset.
2. Perform data preprocessing and feature engineering.
3. Train a baseline LightGBM model.
4. Optimize hyperparameters using cross-validation.
5. Evaluate model performance.
6. Compare results with the Random Forest classifier.
7. Visualize feature importance and model performance.

## Objective

Develop an accurate and efficient multiclass classification model capable of predicting forest cover types to support environmental analysis and land management applications.
