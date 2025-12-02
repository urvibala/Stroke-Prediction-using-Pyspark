# Stroke Prediction System Using PySpark

This project builds a machine learning system to predict stroke risk in patients using PySpark. The dataset contains 5,110 patient records with features like age, hypertension, heart disease, BMI, glucose levels, and smoking status. The main challenge was severe class imbalance (only 5% stroke cases), which was solved using oversampling techniques. Three models were trained and compared: Logistic Regression, Random Forest, and Gradient Boosted Trees. Logistic Regression performed best with 85.9% AUC and 89.5% recall, successfully catching 9 out of 10 actual strokes. The project includes complete data preprocessing, feature engineering, model training, evaluation, and a ready-to-use prediction function that classifies patients as HIGH or LOW stroke risk with probability scores.

## Key Features
- Distributed data processing with PySpark
- Handling imbalanced healthcare data
- Model comparison and evaluation
- Production-ready prediction system

## Tech Stack
PySpark, Machine Learning (Logistic Regression, Random Forest, GBT), Feature Engineering, Model Evaluation

## Results
Best Model: Logistic Regression | AUC: 0.859 | Stroke Detection Rate: 89.5%
