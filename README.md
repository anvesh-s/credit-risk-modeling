# credit-risk-modeling
Machine Learning project using Classification
# Credit Risk Modeling

## Project Overview
This project focuses on **Credit Risk Modeling**, applying **data preprocessing, feature engineering, and machine learning** techniques to improve risk prediction. The goal is to optimize recall while maintaining a robust evaluation framework.

## Dataset
The dataset consists of various features related to credit risk assessment, including:
- **Numerical Features**: Financial metrics, credit scores, and transaction details.
- **Categorical Features**: Customer demographics and credit history.

## Data Preprocessing & Feature Engineering
- **Handled missing values** by removing nulls.
- **Exploratory Data Analysis (EDA)**: 
  - Univariate and bivariate analysis.
  - Plotted graphs for better visualization.
- **Feature Selection**:
  - Used **Variance Inflation Factor (VIF)** for numerical features.
  - Used **Information Value (IV) & Weight of Evidence (WOE)** for categorical variables.
- **Collinearity Check**:
  - Heatmap to visualize correlations.
  - Checked correlation between features and the target variable.

## Handling Class Imbalance
- Used **Under-sampling and Over-sampling** techniques.
- Applied **SMOTE-Tomek** to balance class distribution.

## Model Training & Optimization
- Trained various machine learning models.
- **Hyperparameter tuning using OPTUNA**.
- **Improved recall from 0.74 to 0.94**.

## Model Evaluation
- **ROC & AUC Curve** to measure performance.
- **KS Statistic**, **Rank Ordering**, and **Gini Coefficient** for model validation.

## Results
- Successfully optimized the model to improve recall while maintaining robust evaluation metrics.


