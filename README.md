# 🩸 Blood Donation Prediction using Machine Learning

## 📌 Project Overview
This project aims to predict whether a blood donor will donate blood in **March 2007** based on their **past donation behavior**. Using historical donor data, machine learning classification models are trained and evaluated to help blood banks and healthcare organizations plan blood collection drives more effectively.

---

## 🎯 Problem Statement
Blood donation organizations often face uncertainty in donor participation. This project uses machine learning techniques to analyze previous donation patterns and predict future donations, enabling better decision-making and resource planning.

---

## 📊 Dataset Description
The dataset contains historical blood donation records with the following features:

| Feature | Description |
|------|-----------|
| Recency | Months since last donation |
| Frequency | Total number of donations |
| Monetary | Total blood donated (in c.c.) |
| Time | Months since first donation |
| Target | Donated blood in March 2007 (1 = Yes, 0 = No) |

---

## ⚙️ Machine Learning Models Used
- Logistic Regression  
- Random Forest Classifier  
- Support Vector Machine (SVM)

---

## 🧠 Project Workflow
1. Data Loading and Exploration  
2. Data Cleaning (missing & duplicate values)  
3. Feature Scaling  
4. Train-Test Split  
5. Model Training  
6. Model Evaluation  
7. Model Comparison and Selection  

---

## 📈 Evaluation Metrics
The models are evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 🏆 Results
Multiple machine learning models were compared, and the best-performing model was selected based on evaluation metrics. The final model provides reliable predictions for donor behavior.

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 🚀 Future Enhancements
- Hyperparameter tuning  
- Handling class imbalance (SMOTE)  
- Model deployment using Streamlit  
- Integration with real-time donor databases  

---

## 💡 Use Cases
- Blood banks & hospitals  
- NGOs conducting blood donation drives  
- Healthcare analytics teams  


