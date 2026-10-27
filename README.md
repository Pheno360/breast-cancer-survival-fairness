# Evaluating and Mitigating Age Bias in Breast Cancer Survival Prediction Using Subgroup Threshold Tuning

Overview
This project investigates age-related bias and predictive fairness in five-year breast cancer survival prediction using the METABRIC dataset. It compares three machine learning models—Logistic Regression, Random Forest, and XGBoost—using predictive performance metrics and fairness measures across young, middle-aged, and older patient groups.
The study explores whether adjusting the global decision threshold can balance predictive performance and fairness across age groups. XGBoost achieved the highest ROC-AUC of 0.7322. Lowering its threshold from 0.50 to 0.40 increased recall from 94.30% to 97.99% and reduced the observed demographic parity and equalised odds disparities. However, false positives also increased, and bootstrap confidence intervals did not establish a conclusive fairness improvement. The findings highlight the trade-offs between predictive performance, fairness, and potential clinical risks when applying machine learning to healthcare.

Research Focus

Breast cancer survival prediction
Age-related bias in clinical AI
Machine learning model evaluation
Fairness across age groups
Subgroup threshold tuning
Clinical prediction and fairness metrics

Models

Logistic Regression
Random Forest
XGBoost

Key Areas of Analysis

Exploratory data analysis
Data preprocessing
Model development and evaluation
Age-group subgroup analysis
Selection rate, TPR and FPR
Fairness assessment
Decision-threshold analysis
Subgroup threshold tuning

