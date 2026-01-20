# Telco Customer Churn Prediction (End-to-End)

## Overview
This project predicts customer churn using the Telco Customer Churn dataset.  
It includes EDA, preprocessing, model training, evaluation, and inference.

## Dataset
Telco Customer Churn dataset (target: `Churn`)

## Project Structure
- `notebooks/` → EDA + experiments
- `src/` → training + prediction scripts
- `models/` → saved model artifacts (ignored in git)
- `reports/figures/` → charts for README

## How to Run
1. Create env
2. Train model
3. Run predictions

## Metrics
Main metrics: F1-score, ROC-AUC

## Results (Baseline Models)

| Model | F1-score | ROC-AUC |
|------|----------:|--------:|
| Logistic Regression | 0.607 | 0.835 |
| Random Forest | 0.543 | 0.815 |

**Conclusion:** Logistic Regression performed best and is used as the baseline deployment model.
