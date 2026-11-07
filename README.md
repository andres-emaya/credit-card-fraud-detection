# Credit Card Fraud Detection on Imbalanced Data

📄 [Read the paper](paper/imbalanced-fraud-detection.pdf)

Handling a highly imbalanced dataset (0.17% fraud) with SMOTE, outlier clipping, robust scaling and a soft-voting ensemble of LightGBM, XGBoost and Logistic Regression.

**Results (fraud class):** Precision 0.94 · Recall 0.81 · F1 0.87 · ROC-AUC 0.977

**Dataset:** [Credit Card Fraud Detection (MLG-ULB)](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). Download `creditcard.csv` and place it in the `notebooks/` folder.

**Built with:** Python, scikit-learn, imbalanced-learn, LightGBM, XGBoost