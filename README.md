# Credit card fraud detection

## Problem Statement
Credit card fraud poses a significant global financial threat, with losses reaching tens of billions of dollars annually. According to the United States Sentencing Commission's fiscal year 2023 report, 64,124 fraud cases were reported, affecting an estimated 128 million victims. Three out of five cardholders have experienced unauthorized charges, with 75% of victims reporting multiple instances of fraud. Given the massive volume of transaction data, human analysts can no longer effectively identify fraudulent patterns manually. This project aims to leverage machine learning techniques to create an efficient, automated fraud detection system that can protect financial institutions and their customers from fraudulent activities.

## Goals
(1) Conduct comprehensive performance analysis of different fraud detection systems

(2) Identify the most effective model for real-world fraud detection scenarios based on F1-score, Precision, Recall, AUC ROC metrics

## Dataset
[Credit card fraud dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data)

## Tools: 
* Python, Pandas, NumPy, PySpark, MatplotLib, Seaborn

## Approach
### Machine Learning Algorithms
* Linear Support Vector Machine
* Logistic Regression
* Gradient Boosting Classifier
* Multi-Layer Perceptrons

### Sampling techniques
* Stratified
* SMOTE (Synthetic Minority Over-sampling Technique)
* Random Under Sampling

## Results
* Multi-Layer Perceptrons with Stratified Sampling technique
  * **F1-score: 0.896**
  * **Precision: 0.831**
  * **Recall: 0.972**
  * **AUC ROC: 0.998** 
* Top 5 key predictors based on Gradient Boosting Feature Importance: **V7, V12, V17, Amount, V14** (V-number are PCA features due to confidentiality issue)
