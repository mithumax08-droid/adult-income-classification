# Adult Income Classification

Data cleaning, transformation and classification on the UCI Adult Census Income dataset.

## What I did
- Replaced "?" with NaN, removed 52 duplicate records, standardised income labels
- Built leakage-safe Scikit-learn pipelines (imputation, scaling, encoding)
- Compared a baseline and an improved Logistic Regression model

## Results
| Metric | Baseline | Improved |
|---|---|---|
| Accuracy | 0.8498 | 0.8520 |
| Recall | 0.5895 | 0.6053 |
| F1-score | 0.6526 | 0.6620 |
| ROC-AUC | 0.8874 | 0.9081 |

## Tools
Python, Pandas, NumPy, Scikit-learn

## Files
- cleaning_and_transformation.ipynb: full notebook
- DATA CLEANING AND TRANSFORMATION FOR CLASSIFICATION (PDF): project report
- model_comparison.csv: model results
- adult_income_cleaned.csv: cleaned dataset

Dataset: https://archive.ics.uci.edu/dataset/2/adult
