# Practical Work 5 — Classification

## Dataset

Breast Cancer Wisconsin Diagnostic Dataset.

Source:
https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

## Objective

Select a classification threshold based on the cost of classification errors.

## Model

Logistic Regression.

## Preprocessing

- StandardScaler
- Pipeline

## Evaluation

- Precision
- Recall
- F1-score
- Accuracy
- ROC-AUC
- Average Precision

## Visualizations

- ROC Curve
- Precision-Recall Curve
- Confusion Matrices
- Threshold Cost Plot

## Threshold Selection

The threshold was selected by minimizing the cost of false positive and false negative errors on the validation set.

## Data Leakage Prevention

The model was trained only on the training set.
The validation set was used for threshold selection.
The test set was used for final evaluation.
