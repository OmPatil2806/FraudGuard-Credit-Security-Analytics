🚀 Project: FraudGuard-Credit-Security-Analytics

Developed a FraudGuard-Credit-Security-Analytics system using a complete Machine Learning pipeline to identify fraudulent transactions with high accuracy.
Pipeline Steps:
 1️⃣ Data Exploration & Preprocessing – Handled missing values, encoded categorical features, and scaled numerical data using Standardization and Normalization. Engineered features like Hour, Minute, Day Period, and log-transformed Amount for better model performance.
 
2️⃣ Feature Selection & Engineering – Created row-wise statistics (mean, std, max, min) for anonymized transaction features (V1–V28), improving predictive power. Applied one-hot encoding for categorical variables.

3️⃣ Data Splitting – Stratified train-test split to maintain class distribution and ensure unbiased model evaluation.

4️⃣ Model Definition & Training – Implemented multiple classifiers including Logistic Regression, Random Forest, Gradient Boosting, SVM, LinearSVC, and KNN. Handled class imbalance using class_weight="balanced".

5️⃣ Evaluation & Metrics – Assessed models using classification reports, confusion matrices, ROC-AUC, Log Loss, and regression-style metrics (MSE, RMSE, MAE). Visualized feature importance and confusion matrices for interpretability.

6️⃣ Deployment-Ready Insights – Identified key features impacting fraud detection and prepared the pipeline for real-world application.

This project demonstrates the end-to-end ML workflow, from raw data to interpretable, deployable models, combining statistical analysis, feature engineering, model training, and evaluation for accurate fraud detection.
