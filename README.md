# 🏥 Healthcare Classification Using Machine Learning

🎓 UNCG MSIA | Python | Machine Learning  

---

## 📌 Project Overview
This project focuses on building machine learning models to predict **patient test results** using healthcare-related data.

With a background in histology and lab work, I wanted to explore how predictive analytics can support **faster and more informed clinical decision-making**.

---

## 🎥 Project Walkthrough  
👉 https://youtu.be/PWKqensiMKM?si=_KguJD0ZAAqUzkfq  

---

## 📊 Dataset
- ~55,000 patient records  
- Features include:
  - Age  
  - Admission type  
  - Billing information  
  - Clinical and demographic variables  
- Target: **Multi-class test results**

---

## 🛠️ Workflow

### 1. Data Cleaning & Exploration
- Checked for missing values  
- Explored feature distributions  
- Identified potential data quality issues  

### 2. Feature Engineering
- Created a new feature: **Length of Stay**  

### 3. Preprocessing
- One-hot encoded categorical variables  
- Scaled numerical features  
- Used a **stratified 70/30 train-test split**  

---

## 🤖 Models Used
- Random Forest (baseline + tuned)  
- XGBoost (baseline + tuned)  

---

## 📈 Evaluation Metrics
- Accuracy  
- F1 Score  
- ROC-AUC  

---

## 🔍 Key Results
- Random Forest performed best overall  
- Hyperparameter tuning had minimal impact  
- XGBoost performance decreased after tuning  

---

## 💡 Key Takeaways
- Data quality and feature engineering matter more than model complexity  
- Accuracy alone is not enough for evaluating models  
- Over-tuning can negatively impact performance  
- Interpreting results is just as important as building models  

---

## 🏥 Real-World Impact
This project demonstrates how machine learning can:
- Support clinical decision-making  
- Identify patterns in patient data  
- Improve healthcare efficiency  

---

## ⚙️ Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib  
- Seaborn  

---

## 🚀 Future Improvements
- Address potential class imbalance  
- Explore additional feature engineering  
- Test additional models (Logistic Regression, Neural Networks)  
- Deploy as an interactive dashboard  
