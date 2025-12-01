# MLBA_CustomerChurnPredicition  
# Customer Churn Prediction – Reproducibility Package

## 📌 Overview
This repository contains the complete implementation of our telecom customer churn prediction project.  
It provides a fully reproducible workflow covering:

- Data loading and preprocessing  
- Feature engineering and temporal behavior modelling  
- Training Random Forest, XGBoost, and Logistic Regression models  
- Performance evaluation (ROC, PR curves, confusion matrices)  
- Confidence interval estimation using bootstrapping  
- Fairness and segmentation analysis  
- Business-oriented threshold optimization  

The code has been refactored to meet academic reproducibility standards.

---

## 📁 Repository Contents
- **MLBA-2.ipynb**  
  Loads the dataset, performs preprocessing, and trains Random Forest, XGBoost, and Logistic Regression models.

- **ROC.ipynb**  
  Generates ROC/PR curves, evaluates thresholds, and computes cost-based decision insights.

- **Confidence_Interval.ipynb**  
  Computes 95% bootstrap confidence intervals for Accuracy, Precision, Recall, and F1-score.

- **feactureEnginerring_Fairness_Segmentation/**  
  Contains notebooks for:
  - Time-aware feature engineering  
  - Segment-wise performance (Age, Gender, ARPU tiers)  
  - Fairness and subgroup evaluation  

- **customer_churn_dataset_MASTER.csv**  
  The dataset used for training and testing (505,206 records).

- **requirements.txt**  
  Python dependencies to exactly reproduce the environment.

- **README.md** (this file)

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/dhirajpatil2001/MLBA_CustomerChurnPredicition.git
cd MLBA_CustomerChurnPredicition
