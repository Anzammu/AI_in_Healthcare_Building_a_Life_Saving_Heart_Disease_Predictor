🩺 ***Heart Disease Prediction — Machine Learning Project***

📌 Project Overview

    This project focuses on predicting the presence of heart disease in patients based on medical attributes.
    It demonstrates the full workflow of a supervised classification task:
    
    Exploratory Data Analysis (EDA) — understanding the dataset, distributions, and relationships.
    
    Preprocessing — handling missing values, encoding categorical features, and scaling numerical features.
    
    Model Training (without Pipelines) — applying preprocessing manually and training classification models.
    
    Model Evaluation — assessing models with metrics such as Accuracy, Precision, Recall, F1-score, and Confusion Matrix.
    
    Feature Importance — identifying the most influential medical factors for predicting heart disease.


🔑 Key Concepts Covered

    Classification Fundamentals (Binary Classification: disease vs. no disease)
    
    EDA Techniques: visualizations, correlation analysis, class distribution check
    
    Data Preprocessing: imputation, scaling, one-hot encoding
    
    Model Training: Logistic Regression (baseline) and Random Forest (ensemble model)
    
    Evaluation Metrics: Accuracy, Precision, Recall, F1, Confusion Matrix
    
    Healthcare Insight: why Recall is especially important in medical contexts

    

⚙️ Technologies & Libraries

    Python
    
    Pandas, NumPy
    
    Matplotlib, Seaborn
    
    Scikit-learn (Logistic Regression, Random Forest, Preprocessing, Metrics)

    

📊 Results Summary

    Logistic Regression provided a strong baseline.
    
    Random Forest achieved better performance overall, especially in Recall and F1-score.
    
    The most important features for prediction included age, cholesterol, blood pressure, and heart rate.
    
    In a healthcare context, prioritizing Recall is crucial to minimize false negatives (avoiding missed diagnoses).
