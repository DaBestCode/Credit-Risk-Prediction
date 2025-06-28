💳 Credit Risk Modeling with XGBoost and Optuna
This project builds a machine learning model to predict credit default risk — a critical problem in financial institutions. We use XGBoost, a high-performance gradient boosting algorithm, along with Optuna for hyperparameter optimization. The dataset contains information on loan applicants and whether they defaulted, and the model predicts creditworthiness based on these features.

📌 Project Overview
The notebook walks through a complete ML pipeline:

Data Preprocessing

Missing value handling

Encoding categorical variables

Scaling numerical features

Handling Imbalanced Classes

Uses SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset

Ensures the model does not favor the majority class

Modeling with XGBoost

Uses XGBClassifier from the XGBoost library

Well-suited for tabular data and imbalanced classification tasks

Hyperparameter Tuning with Optuna

Automates tuning of critical parameters like max_depth, eta, gamma, etc.

Objective is to maximize the macro F1-score using cross-validation

Evaluation

Uses cross_val_score for robust evaluation

Tracks performance across trials to find optimal hyperparameters
