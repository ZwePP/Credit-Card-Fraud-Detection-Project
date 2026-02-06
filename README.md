# Fraud Detection Using Machine Learning

## Overview

This project focuses on detecting fraudulent transactions using machine learning techniques. The dataset is cleaned and balanced to contain **50% fraud and 50% non-fraud** samples. Two classification models are implemented and compared: **Logistic Regression** and **XGBoost**.

## Dataset

- Transaction dataset with numerical features
- Target column: `Class`
  - `0` → No Fraud
  - `1` → Fraud
- Data is preprocessed, scaled, and balanced before model training

## Data Splitting

The dataset is divided into three subsets:

- **Training set** – used to train the models
- **Validation set** – used for model comparison and tuning
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

- Logistic Regression achieved an **Average Precision (AP) score of approximately 0.94**
- XGBoost achieved a higher **Average Precision (AP) score of approximately 0.96**
- Both models show strong and stable performance on validation and test datasets
- Precision–Recall curves indicate that both models effectively balance precision and recall, with XGBoost providing a slightly better ranking of fraudulent transactions

## Conclusion

Both Logistic Regression and XGBoost generalize well to unseen data. Logistic Regression performs well when making high-confidence predictions, while XGBoost demonstrates superior performance in ranking fraud cases across different thresholds. Overall, XGBoost is more suitable for scenarios where higher fraud detection coverage is required.

## Tools and Libraries

- Python
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

## How to Run

1. Open the Jupyter Notebook (`Group2.ipynb`)
2. Run all cells in order
3. Review the model evaluation results and graphs
