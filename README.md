# Predicting Transaction Fraud with Machine Learning

This repository contains the final exam project for the Machine Learning course at Copenhagen Business School. The goal was to build a classification model to detect fraudulent financial transactions using a heavily imbalanced dataset.

## 🧠 Project Overview

The task involved:
- Handling class imbalance manually (without SMOTE or undersampling).
- Building a machine learning pipeline for binary classification.
- Comparing multiple models and evaluating performance using Recall.
- Conducting feature engineering and exploratory data analysis (EDA).
- Delivering a professional report with justifications and results.

## 📂 Structure
```
📁 Processed Dataset/  
    └── Cleaned CSVs used during training

📁 Raw Datasets/  
    └── [Note: Full transaction file omitted due to >1GB size]

📄 ML - Final Exam - Python Code - Brian Rohde and Enrico Manfron.ipynb  
📄 ML - Final Exam - Report - Brian Rohde and Enrico Manfron.pdf
```


⚠️ **Note:** The full raw dataset (1GB+) could not be uploaded to GitHub due to size limitations.

## ⚙️ Technologies Used

- Python (Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn)
- Jupyter Notebook
- Google Colab
- LaTeX (for the final report)

## 🏁 Results Summary

- **Baseline Model:** Logistic Regression
- **Best Performing Model:** XGBoost (Highest Recall on Test Set)
- Custom manual class balancing approach outperformed naive baseline strategies.

## 📑 Report

The full report (`ML - Final Exam - Report - Brian Rohde and Enrico Manfron.pdf`) provides detailed methodology, evaluation metrics, visualizations, and conclusions.

## 👥 Authors

- **Brian Rohde**  
- **Enrico Manfron**

This project was submitted as part of the MSc Business Administration & Data Science program at CBS.
