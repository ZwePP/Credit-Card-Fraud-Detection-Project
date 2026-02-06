# Fraud Detection Using Machine Learning

## Overview

This project focuses on detecting fraudulent transactions using machine learning models. The dataset is preprocessed and balanced to contain **50% fraud and 50% non-fraud** samples. Two models are trained and evaluated: **Logistic Regression** and **XGBoost**.

## Dataset

- The dataset contains transaction features and a target column `Class`
- `Class = 0` → No Fraud
- `Class = 1` → Fraud
- Data is cleaned and balanced before training

## Data Splitting

The dataset is split into:

- **Training set** – used to train the models
- **Validation set** – used to tune and compare models
- **Test set** – used for final evaluation on unseen data

## Models Used

- Logistic Regression
- XGBoost Classifier

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Confusion Matrix
- Precision, Recall, and F1-score
- Precision–Recall Curve
- Average Precision (AP)

## Results

- Both models achieved strong performance on validation and test datasets
- Precision–Recall curves show a good balance between precision and recall
- XGBoost performs slightly better in detecting fraud cases at higher recall levels

## Conclusion

Both Logistic Regression and XGBoost generalize well to unseen data. Logistic Regression performs well with high-confidence predictions, while XGBoost provides a better trade-off when higher fraud detection coverage is required.

## Tools and Libraries

- Python
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

## How to Run

1. Open the Jupyter Notebook (`Group2.ipynb`)
2. Run all cells in order
3. Review model evaluation results and graphs
