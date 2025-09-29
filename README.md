# ❤️ Heart Disease Analysis Project

This project is part of my Data Analysis portfolio. It focuses on exploring and analyzing a **Heart Disease Dataset** to uncover important risk factors and patterns that may contribute to cardiovascular disease.  
The analysis was performed using **feature engineering, data preprocessing, and exploratory data analysis (EDA)** techniques.


---

## 📌 Project Objectives
1. Perform **data preprocessing** (handle missing values, duplicates, outliers, and imbalance).  
2. Apply **feature engineering** to create meaningful features for better analysis.  
3. Conduct **EDA** to identify important health-related patterns in the dataset.  
4. Provide **insights and conclusions** on the relationship between key factors (blood pressure, cholesterol ratio, age) and the risk of heart disease.  

---

## 🛠️ Data Preprocessing
The preprocessing steps included:
- **Handling missing values & duplicates**  
- **Detecting and treating outliers**  
- **Balancing the dataset** for fair analysis  
- **Feature engineering** to transform raw medical data into interpretable features  

---

## 📊 Exploratory Data Analysis (EDA)

### 1. Blood Pressure Distribution
- Blood pressure levels were categorized into:
  - **Normal** (<130 mmHg)  
  - **High-Normal** (131–139 mmHg)  
  - **High** (≥140 mmHg)  
- **Result:** 62.5% of patients had **high blood pressure**, showing it as a key risk factor.

---

### 2. Cholesterol Ratio vs Heart Disease Risk
- Ratio calculated between `chol` (cholesterol) and `thalach` (maximum heart rate achieved).  
- **Result:** Patients with **higher cholesterol ratios** had a greater risk of heart disease, while lower ratios were observed in healthier patients.  

---

### 3. Age Distribution
- The **mode age** of patients was **60 years**.  
- Patients above **60 years old** had the highest heart disease risk.  
- Patients **under 30 years** had significantly lower risk.  

---

## ✅ Key Insights & Conclusion
1. **High blood pressure** is strongly correlated with higher heart disease risk (62.5% of patients).  
2. **Cholesterol ratio** is a critical factor, where higher ratios indicate higher risk.  
3. **Age** is a major determinant: older patients are more prone to heart disease.  

📌 Overall, patients with **high blood pressure, high cholesterol, and advanced age** are at the greatest risk of developing heart disease.  

---

## 📦 Tech Stack
- **Python**  
- **Pandas & NumPy** – Data preprocessing & feature engineering  
- **Matplotlib & Seaborn** – Data visualization  
- **Jupyter/Colab** – Analysis environment  

