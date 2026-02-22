Fraud Detection using PCA & NMF

This project applies dimensionality reduction techniques (PCA and NMF) as feature engineering methods for credit card fraud detection.

The goal is to evaluate whether reducing feature space improves model efficiency while maintaining fraud detection performance under severe class imbalance.

Key Steps

 - Data preprocessing and stratified train-test split

 - Baseline Logistic Regression model

 - PCA feature reduction (variance-based selection)

 - NMF feature extraction (non-negative matrix factorization)

 - Performance evaluation using ROC-AUC, precision, and recall

Results

 - Compared baseline vs PCA vs NMF pipelines

 - Evaluated trade-off between dimensionality reduction and fraud recall

 - Analyzed performance under imbalanced data conditions

Dataset

  kaggle

Tools

  Python, pandas, scikit-learn, matplotlib
