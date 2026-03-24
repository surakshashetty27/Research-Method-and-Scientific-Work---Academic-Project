# Research-Method-and-Scientific-Work---Academic-Project
**Project Overview**
This project develops an advanced Employee Attrition Prediction Pipeline using machine learning techniques to identify employees at risk of leaving. The pipeline includes data preprocessing, handling class imbalance using SMOTE, feature scaling, and training multiple optimized models. It also incorporates ensemble learning through a Voting Classifier to improve predictive performance. The project focuses on building a robust and reliable system for HR analytics and decision-making.

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
- Feature importance analysis using Random Forest
- Visual comparison of model performance

**Results**
The models were evaluated using multiple performance metrics, with the Voting Classifier achieving the best performance at 90.00% accuracy and 85.00% F1-score, followed closely by Random Forest with 89.00% accuracy. Logistic Regression also performed strongly with over 85% accuracy. The use of SMOTE for class balancing and hyperparameter tuning significantly improved model performance. Overall, the pipeline demonstrates strong predictive capability and provides reliable insights for identifying employees at risk of attrition.
