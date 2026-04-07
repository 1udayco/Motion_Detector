# Motion_Detector

# Motion & Fall Detection using Machine Learning

This project implements a professional Machine Learning pipeline to classify human activities such as **idle, step, motion, and fall** using sensor dataset features.

## 🚀 Features
- Data preprocessing using Scikit-Learn Pipeline
- Label Encoding for categorical targets
- Missing value imputation and feature scaling
- Random Forest Classifier with hyperparameter tuning
- Cross-validation for robust performance
- Evaluation using Confusion Matrix, F1-score, ROC-AUC
- Model export for deployment using joblib

## 🧠 ML Workflow
1. Load dataset
2. Preprocess and encode labels
3. Train-test split with stratification
4. Pipeline creation (Imputer + Scaler + Classifier)
5. Hyperparameter tuning with RandomizedSearchCV
6. Model evaluation with plots
7. Save trained model

## 📊 Evaluation Metrics
- Accuracy
- Precision / Recall / F1-score
- Confusion Matrix
- ROC Curve & AUC score (multiclass)

## 🛠 Tech Stack
- Python
- Pandas, NumPy
- Scikit-Learn
- Matplotlib
- Joblib

## 📁 Project Structure
