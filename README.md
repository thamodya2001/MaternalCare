
# 🤰MaternalCare AI: A Web-Based Application for Predicting Maternal Health Risk Using Clinical Data

Maternal health risk prediction plays a vital role in the early detection of pregnancy complications, particularly in resource-limited settings. This project focuses on identifying key risk factors and classifying maternal risk levels into **high** and **low** categories using clinical and demographic data.  

The analysis was performed on a cleaned dataset of **1,187 patient records** with **12 variables**. Exploratory data analysis revealed that elevated **blood pressure**, **blood sugar levels**, **BMI**, and **pre-existing conditions** are strongly associated with higher maternal risk.  

To improve predictive performance, several machine learning models were evaluated, including **Random Forest, SVM, XGBoost, and Neural Networks**. Among these, a **Stacking Ensemble Model**—combining Random Forest and SVM as base learners with a Lasso final estimator—achieved the best results, with **98% accuracy, precision, and recall**.  

Additionally, **SHAP (SHapley Additive exPlanations)** analysis identified **high systolic blood pressure** and **advanced maternal age** as the most influential factors in predicting high-risk cases.  

These findings demonstrate the strong potential of data-driven approaches to assist healthcare professionals in prioritizing patient care and optimizing resource allocation.  

🚀 A **Streamlit web application** has been developed to make this model accessible for real-world use.  
👉 Check out the repository here: *(https://github.com/thamodya2001/maternelcare_webapp)*  
