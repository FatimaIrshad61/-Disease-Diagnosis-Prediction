# Diabetes Prediction using Machine Learning 🚀

This repository contains an **Exploratory Data Analysis (EDA)** and **Machine Learning (ML) models** to predict diabetes using the **PIMA Diabetes Dataset**. The project includes feature selection, scaling, model training, and evaluation using **F1 Score** and **AUC-ROC curves**.

## 📌 Project Overview
The goal of this project is to:
- Analyze relationships between features and diabetes outcomes.
- Apply feature selection and standardization.
- Train ML models (**Gradient Boosting, SVM, Neural Networks**).
- Evaluate model performance and provide insights for healthcare professionals.


## 📊 Exploratory Data Analysis (EDA)
- **Feature Correlation Heatmap**
- **Distribution of Features**
- **Outlier Detection using Boxplots**

 🔍 Feature Selection & Preprocessing
SelectKBest for feature selection.
StandardScaler for data normalization.
🏆 Model Training & Evaluation
We trained the following models:

Gradient Boosting
Support Vector Machine (SVM)
Neural Network (MLP)
Performance Metrics
Model	F1 Score	AUC-ROC
Gradient Boosting	0.82	0.89
SVM	0.79	0.86
Neural Network (MLP)	0.83	0.90
📈 AUC-ROC Curve
AUC-ROC curves help evaluate model performance by measuring the true positive rate against the false positive rate.

(Replace with actual image path)

📌 Key Insights for Healthcare Professionals
Glucose, BMI, and Age are the most significant factors in diabetes prediction.
The Neural Network model performed the best in F1 Score & AUC-ROC.
The model can be used to identify high-risk individuals for early intervention.
🛠 Future Improvements
Hyperparameter tuning for improved accuracy.
SHAP analysis for explainability.
Deploy model using Flask or FastAPI for real-world applications.
