# Regression with an Insurance Dataset


## Overview
This project is a submission for the [Playground Series - Season 4, Episode 12](https://www.kaggle.com/competitions/playground-series-s4e12) Kaggle competition. The goal of the competition is to predict insurance outcomes based on the provided dataset, which contains anonymized features and target variables.

## Dataset
The dataset is provided by Kaggle and consists of:
- **Training data**: Features and target variable for model training.
- **Test data**: Features for which predictions need to be made.
- **Sample submission**: A template for the submission format.

Key characteristics of the dataset:
- Features are anonymized (`feature_1`, `feature_2`, ..., `feature_n`).
- The target variable is `target` (binary classification: `0` or `1`).

Access the dataset [here](https://www.kaggle.com/competitions/playground-series-s4e12/data).

## Objective
The main objective is to build a machine learning model that accurately predicts the target variable (`target`) using the given features.

## Project Steps
1. **Exploratory Data Analysis (EDA):**
   - Analyzed the distribution of features and the target variable.
   - Checked for missing values, correlations, and potential outliers.

2. **Data Preprocessing:**
   - Standardized/normalized features for improved model performance.
   - Handled missing values (if any) and created additional derived features.

3. **Modeling:**
   - Experimented with multiple models, including:
     - Gradient Boosting (XGBoost, LightGBM)
   - Used cross-validation techniques to evaluate model performance.

4. **Hyperparameter Tuning:**
   - Applied techniques like Grid Search and Bayesian Optimization to fine-tune model parameters.

5. **Evaluation Metrics:**
   - Focused on **Area Under the Receiver Operating Characteristic Curve (AUC-ROC)** as the primary evaluation metric.

6. **Submission:**
   - Generated predictions for the test set and created a submission file in the required format.

## Results
| Model               | AUC-ROC Score (CV) | AUC-ROC Score (Test) |
|---------------------|--------------------|-----------------------|
| XGBoost             | X.XXXX            | X.XXXX               |
| LightGBM            | X.XXXX            | X.XXXX               |


