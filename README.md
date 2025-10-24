# Diabities-detection
: Diabetes Prediction Using Machine
Learning
Project Overview
This repository contains the implementation and analysis of the research project titled
"Comparative Performance Evaluation of Logistic Regression, Random Forest, and
XGBoost Models for Diabetes Prediction on the CDC BRFSS Dataset". The study
investigates how machine learning models can be applied to predict diabetes risk based
on non-invasive, self-reported health data from the CDC Behavioral Risk Factor
Surveillance System (BRFSS).
Dataset
The dataset used is the CDC Diabetes Health Indicators dataset, derived from the 2015
BRFSS survey, available through the UCI Machine Learning Repository. It includes
253,680 records and 21 features representing demographic, behavioral, and
health-related variables. The target variable Diabetes_012 has three categories: 0 = No
diabetes 1 = Pre-diabetes 2 = Diabetes
Objectives
1. Develop and evaluate three machine learning models (Logistic Regression, Random
Forest, XGBoost) for diabetes prediction.
2. Compare model performance using Accuracy, Precision, Recall, F1-score, and
Confusion Matrices.
3. Identify the most influential health and demographic features associated with diabetes
risk.
4. Assess potential public health applications for early detection using AI-driven models
   Methodology Summary
The study used an 80/20 stratified train-test split to evaluate three supervised learning
models: Logistic Regression – Linear baseline model for interpretability. Random Forest
– Ensemble model that captures non-linear feature interactions. XGBoost – Gradient
boosting model optimized for speed and imbalanced data. Data preprocessing included
normalization for continuous features (BMI, Age) and correlation analysis to identify key
predictors. Evaluation metrics were computed using Scikit-learn, while visualizations were
created with Matplotlib and Seaborn.
Results Summary
XGBoost achieved the highest accuracy (≈85%) and most balanced classification
performance. Random Forest performed robustly but struggled to identify pre-diabetes
cases due to class imbalance. Logistic Regression provided interpretability but lower
predictive power (≈65% accuracy). Most influential features: High Blood Pressure, General
Health, High Cholesterol, Cholesterol Check, BMI, and Age.
Healthcare Implications
Machine learning-based predictive models can support early diabetes risk detection using
non-invasive survey data. Such tools can be integrated into public health systems, mobile
health applications, and electronic health records (EHRs) to identify high-risk individuals
and enable proactive intervention strategies.
Limitations & Future Work
The main limitations include class imbalance, reliance on self-reported data, and limited
temporal generalizability (2015 dataset). Future research should focus on: Incorporating
multi-year BRFSS data for temporal stability. Applying resampling techniques (e.g.,
SMOTE) for better class balance. Using explainable AI tools (SHAP, LIME) to improve
model transparency. Integrating clinical biomarkers and deep learning architectures.
