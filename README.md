# credit-card-fraud-detection
Machine learning project for detecting fraudulent transactions under extreme class imbalance
Project Overview
This project focuses on detecting fraudulent credit card transactions from a highly imbalanced dataset (0.17% fraud cases). The goal was to maximize fraud detection recall while maintaining model robustness.

Dataset
Credit Card Fraud Dataset (Kaggle)  
- Total transactions: 284,807  
- Fraudulent transactions: 492 (0.17%)

Tools & Technologies
- Python (Pandas, NumPy)
- Scikit-learn
- Matplotlib, Seaborn

Approach
- Performed exploratory data analysis to understand transaction patterns
- Addressed extreme class imbalance
- Trained and tuned Logistic Regression, SVM, and KNN models using GridSearchCV
- Evaluated models using Recall, F1-score, ROC-AUC, and Confusion Matrix

Results
- Achieved **93% recall** on fraudulent transactions
- Logistic Regression provided the best balance between recall and interpretability

 Files
- `fraud_detection.ipynb`: End-to-end analysis, modeling, and evaluation
- `requirements.txt`: Project dependencies
