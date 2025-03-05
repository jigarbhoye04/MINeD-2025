# Project: Malware Detection Using Machine Learning

## Overview

This project focuses on **malware detection using machine learning** techniques. We analyze software based on API call-related attributes to classify it into one of six types. The goal is to detect malware effectively by leveraging advanced data processing and machine learning algorithms .

## Data

The project uses the following dataset files:
- `portable_executable.csv`
- `DLLs_Imported.csv`
- `API_Functions.csv`
- `test.csv` (test dataset)

### Dataset Overview
- **Attributes**: The dataset contains around **22,000 attributes**.
- **Features**: Key features include API call-related attributes for classification.

## Feature Engineering

In order to reduce dimensionality, the following techniques are applied:
2. **Correlation Matrix**: To remove highly correlated features.
3. **Extra Trees Classifier**: For feature selection.

## Approach

The project follows these steps:
1. **Data Loading and Preprocessing**:
   - Load the CSV files.
   - Perform data cleaning and preprocessing (handling missing values, scaling, etc.).
   
2. **Feature Engineering**:
   - Use the correlation matrix to identify redundant features.
   - Apply Extra Trees for feature selection.
   - Use SMOTE to fix imbalanced data.

3. **Model Selection**:
   - Train three models:
     - **XGBoost**
     - **Random Forest**
     - **Light GBM**
   
4. **Evaluation**:
   - Evaluate the models' performance using suitable metrics (accuracy, precision, recall, etc.).
   - Perform hyperparameter tuning if needed.
   
## Requirements

- **Python** (3.x)
- **Libraries**:
  - pandas
  - numpy
  - scikit-learn
  - xgboost
  - imbalanced-learn
  - matplotlib
  - seaborn

to run this code goto notebooks and run individual code.
