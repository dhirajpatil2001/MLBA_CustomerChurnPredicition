# MLBA_CustomerChurnPredicition

# Customer Churn Prediction - Reproducibility Package

## Overview
This repository contains code and resources for predicting customer churn using machine learning. It offers a step-by-step workflow from data preprocessing and model training to evaluation and uncertainty quantification.

## Repository Contents
- **MLBA-2.ipynb**: Load and analyze customer churn data, build and validate a Random Forest model with train/test/validation splits.
- **ROC.ipynb**: Train Logistic Regression and Random Forest models, evaluate using precision-recall curves and optimize classification thresholds.
- **Confidence_Interval.ipynb**: Calculate bootstrap confidence intervals for evaluation metrics like accuracy, precision, recall, and F1-score.

## Getting Started
To reproduce the results:
1. Clone this repository:
   ```
   git clone https://github.com/dhirajpatil2001/MLBA_CustomerChurnPredicition.git
   ```
2. Install required packages (example using pip):
   ```
   pip install pandas numpy scikit-learn matplotlib
   ```
3. Place the dataset file `customer_churn_dataset_MASTER.csv` in the appropriate folder or update file paths in the notebooks.
4. Open and run the notebooks in order using Jupyter Notebook or JupyterLab to follow the analysis.

## For Non-Experts
Even without advanced coding knowledge, users can open the Jupyter notebooks in any web browser interface supporting Jupyter and run each cell step-by-step to replicate the analyses.

## Reproducibility
The experiments are fully reproducible with well-documented preprocessing, model parameters, and evaluation procedures ensuring consistent results.


***

Let me know if you want me to create a LICENSE file or provide a requirements.txt file.
