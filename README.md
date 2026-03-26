# Research-Method-and-Scientific-Work---Academic-Project
**Project Overview**
This project develops an advanced Employee Attrition Prediction Pipeline using machine learning techniques to identify employees at risk of leaving. The pipeline includes data preprocessing, handling class imbalance using SMOTE, feature scaling, and training multiple optimized models. It also incorporates ensemble learning through a Voting Classifier to improve predictive performance. The project focuses on building a robust and reliable system for HR analytics and decision-making.

**Business Problem**
Employee attrition is a major challenge for organizations, leading to increased recruitment costs, loss of experienced talent, and reduced overall productivity. Companies often struggle to identify the underlying factors causing employees to leave and lack proactive strategies to address these issues.
The business problem addressed in this project is to predict which employees are at risk of leaving the organization based on historical HR data. By leveraging machine learning, the goal is to uncover key drivers of attrition and enable HR teams to take data-driven, proactive actions to improve employee retention, reduce turnover costs, and maintain workforce stability.

**Dataset**
https://data.mendeley.com/datasets/6z2hty8php/1

**Key Features**
- End-to-end machine learning pipeline from preprocessing to evaluation
- Handling imbalanced data using SMOTE (Synthetic Minority Oversampling Technique)
- Label encoding for categorical variables
- Feature scaling using StandardScaler
- Train-test split with stratification (80/20)
- Training multiple models:
    Logistic Regression
    Decision Tree
    Random Forest
    SVM (Support Vector Machine)
- Hyperparameter tuning for improved model performance
- Ensemble learning using Voting Classifier (soft voting)
- Model evaluation using Accuracy, Precision, Recall, and F1-score
- Visual comparison of model performance

**Results**
The models were evaluated using multiple performance metrics, with the Voting Classifier achieving the best performance at 84.52 % accuracy and 84.47% F1-score, followed closely by Random Forest with 82.85% accuracy. Logistic Regression also performed strongly with over 85% accuracy. 
