# Binary Classification of Insurance Cross Selling

This project is part of the 2024 Kaggle Playground Series, where the goal is to predict which customers respond positively to an automobile insurance offer.

## Overview
The objective of this competition is to build a binary classification model that predicts the likelihood of a customer responding positively to an insurance offer. The project involves data preprocessing, exploratory data analysis, model training, and hyperparameter tuning using XGBoost and CatBoost.

## Dataset
The dataset consists of customer information and their response to the insurance offer.

Link : 
https://www.kaggle.com/datasets/anmolkumar/health-insurance-cross-sell-prediction/data

### Files
- `train.csv`: Training dataset with features and target variable `Response`.
- `test.csv`: Test dataset where you need to predict the probability of `Response`.

## Evaluation
The model's performance is evaluated using the ROC AUC score. The best ROC AUC score achieved by the model is `0.8764`.

## Usage

### Clone the repository
```bash
git clone https://github.com/your-username/Binary-Classification-Insurance-Cross-Selling.git
cd Binary-Classification-Insurance-Cross-Selling
