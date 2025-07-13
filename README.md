# Bank Customer Subscription Prediction

A machine learning classification project using Scikit-learn pipelines to predict whether a customer will subscribe to a term deposit — based on the **UCI Bank Marketing Dataset**.

## Objectives
- Predict customer term deposit subscription.
- Implement end-to-end pipelines for preprocessing and modeling.
- Evaluate multiple classification models for performance.
- Derive actionable insights to improve marketing strategy.

## Dataset
- Source: [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- 11,162 customer records
- Features include age, job, education, marital status, contact method, campaign outcomes, etc.

## Models Compared
- **Random Forest** (Best performer)
- Decision Tree
- Support Vector Machine (SVM)
- Naïve Bayes

## Evaluation Metrics
- Accuracy, Precision, Recall, F1-Score
- ROC-AUC
- Confusion Matrix & ROC Curve Visualizations

## Key Insights
- **Contact duration**, **month of contact**, and **previous outcome** are top predictors.
- **Random Forest** achieved:
  - 91% Accuracy  
  - 0.88 ROC-AUC  

## Tools & Technologies
- Python
- Scikit-learn (Pipelines)
- Pandas & NumPy
- Matplotlib & Seaborn
- Jupyter Notebook
