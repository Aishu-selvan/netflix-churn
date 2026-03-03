# 🎬 Netflix Customer Churn Prediction

## 📌 Project Overview
This project builds a Machine Learning model to predict whether a customer will churn from a Netflix-like streaming platform.  
The goal is to help businesses identify customers who are likely to leave and take proactive retention actions.

---

## 📊 Dataset
The dataset contains **1000 customer records** with behavioral, demographic, and subscription-related features.

### Feature Examples
- Subscription Length
- Customer Satisfaction Score
- Daily Watch Time
- Engagement Rate
- Support Queries Logged
- Age & Monthly Income
- Device Used & Genre Preference
- Payment History
- Subscription Plan

**Target Variable**
- `Churn`  
  - 1 → Customer churned  
  - 0 → Customer retained

---

## 🔍 Exploratory Data Analysis (EDA)
Key findings:
- Churn distribution is balanced.
- No single feature strongly predicts churn.
- Behavioral factors influence churn more than demographics.
- Payment delays and support issues show higher churn tendency.

---

## ⚙️ Model Used
- **Random Forest Classifier**

Why Random Forest?
- Handles nonlinear relationships
- Works well with mixed data types
- Reduces overfitting using ensemble learning

---

## 🧪 Model Evaluation
Metrics used:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

**Model Accuracy:** ~52%

The model achieves better recall for churn customers, making it useful for identifying at-risk users.

---

## 💼 Business Insights
- Customer behavior impacts churn more than subscription plans.
- Higher support queries indicate dissatisfaction.
- Payment delays increase churn risk.
- Engagement improvement can reduce churn.

---

## 🚀 Future Improvements
- Try XGBoost or LightGBM
- Feature engineering
- Hyperparameter tuning
- Model deployment improvements

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Flask (for deployment)

---

## ✅ Conclusion
This project demonstrates an end-to-end Machine Learning workflow including data analysis, preprocessing, modeling, evaluation, and business interpretation for customer churn prediction.
