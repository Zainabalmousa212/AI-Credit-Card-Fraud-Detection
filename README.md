# AI-Based Credit Card Fraud Detection System

## Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques.

Due to the highly imbalanced nature of the dataset, SMOTE (Synthetic Minority Oversampling Technique) was applied to improve fraud detection performance.

## Dataset

- Source: Kaggle Credit Card Fraud Detection Dataset
- Total Transactions: 284,807
- Fraud Cases: 492
- Fraud Rate: 0.17%

Features:
- V1–V28 (PCA-transformed features)
- Time
- Amount

Target:
- Class = 0 (Legitimate)
- Class = 1 (Fraudulent)

---

## Methodology

1. Data Preprocessing
2. Feature Scaling using StandardScaler
3. Class Imbalance Handling using SMOTE
4. Model Training
    - Logistic Regression
    - Decision Tree
    - Random Forest
5. Hyperparameter Tuning using GridSearchCV
6. Model Evaluation

---

## Results

| Model | Accuracy | Precision | Recall | F1 |
|---------|---------|---------|---------|---------|
| Logistic Regression | 97.3% | 5.3% | 87.3% | 10.0% |
| Decision Tree | 99.7% | 39.2% | 69.4% | 50.1% |
| Random Forest | 99.95% | 92.41% | 76.84% | 83.91% |

### Best Model
Random Forest achieved the best overall performance.

AUROC = 0.9519

---

## Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- SMOTE
- GridSearchCV

---

## Team Members

- Zainab AlMousa
- Renad Aleid
- Shaikhah Aldossary
- Fatimah Alalawi
- Sara Buarish
- Fatimah Alnasser

Supervisor:
- Dr. Sarah Alyami
