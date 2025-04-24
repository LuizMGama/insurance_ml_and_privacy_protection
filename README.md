# 🛡️ Project: Insurance ML Models and Privacy Protection

## 🎯 Project Objective  
The insurance company **Proteja Seu Amanhã** wants to evaluate the potential of machine learning to support decision-making and marketing tasks.  
This project tackles four key objectives:

1. **Customer Similarity:** Find clients most similar to a given customer (for marketing segmentation).
2. **Binary Classification:** Predict whether a new client will receive any insurance payments.
3. **Regression Modeling:** Estimate the expected number of insurance payments.
4. **Data Privacy:** Apply data obfuscation (masking) techniques to protect client data without degrading model performance.

---

## ✅ Results Achieved  
- Cleaned and explored customer data (gender, age, income, family size, insurance history)  
- Used **Nearest Neighbors** algorithm to retrieve similar customers  
- Built a **K-Nearest Neighbors classifier** to predict if a client will receive a benefit  
- Trained a **Linear Regression model** to predict how many insurance claims a client might have  
- Applied a **linear data transformation for masking (Ax+b)** to anonymize the data  
- Verified that model quality was not affected by the masking process

---

## 🛠️ Tools and Technologies Used  
- **Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn  
- **ML Techniques:**
  - Nearest Neighbors search
  - KNN classification
  - Linear Regression
  - Data obfuscation using matrix multiplication
- **Evaluation metrics:**
  - F1-score
  - RMSE
  - R²

---

## 🚀 Skills Developed  
- Customer segmentation using similarity models  
- Building classification and regression models for insurance datasets  
- Data transformation for privacy without information loss  
- Critical evaluation of model performance  
- Data storytelling and structured experimentation

---

## 🔧 Future Improvements  
- Test additional classifiers (e.g., Random Forest, Gradient Boosting)  
- Enhance data masking with non-linear transformations  
- Implement privacy-preserving techniques like differential privacy  
- Expand dataset to include more features like claim types or durations
