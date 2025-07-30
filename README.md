# Student_Performance_Analysis
# 🎓 Capstone Project: Student Performance Analysis & Prediction

**Course:** INSY 8413 – Introduction to Big Data Analytics  
**Institution:** Adventist University of Central Africa (AUCA)  
**Instructor:** Eric Maniraguha  
**Student:** Lesly Akanyana  
**Year:** 2025

---

## 📌 Project Overview

This capstone project explores student performance by analyzing demographic and educational factors to uncover trends and make predictive insights. The project uses a **real-world dataset** from the **Open University Learning Analytics Dataset (OULAD)** and applies **Python for data analysis & machine learning**, and **Power BI for visualization and dashboarding**.

---

## 🎯 Objectives

- To clean, preprocess, and analyze student data from a virtual learning platform.
- To build a predictive model that classifies student outcomes (Pass/Fail/Withdraw/Distinction).
- To design an interactive Power BI dashboard highlighting key performance indicators (KPIs).
- To derive actionable insights for academic stakeholders to improve learning strategies.

---

## 🧾 Dataset Used

**Filename:** `studentInfo.csv`  
**Source:** UCI Machine Learning Repository – [OULAD Dataset](https://archive.ics.uci.edu/ml/datasets/Open+University+Learning+Analytics+Dataset)

### Key Columns:
- `id_student`: Unique student ID  
- `gender`: Male/Female  
- `region`: Geographic location  
- `highest_education`: Student's prior education level  
- `imd_band`: Socioeconomic indicator  
- `age_band`: Age group  
- `disability`: Disability status  
- `final_result`: Target variable – final outcome of student (Pass/Fail/etc.)

---

## 🛠️ Technologies & Tools

| Category            | Tools/Technologies                          |
|---------------------|---------------------------------------------|
| Programming         | Python 3 (Pandas, Seaborn, scikit-learn)    |
| Machine Learning    | RandomForestClassifier (classification)     |
| Data Visualization  | Matplotlib, Power BI                        |
| BI & Reporting      | Microsoft Power BI Desktop                  |
| Notebook Platform   | Jupyter Notebook                            |
| Version Control     | Git + GitHub                                |

---

## 🔍 Python Analysis Summary (`Student_Performance.ipynb`)

### Steps Performed:
1. **Data Cleaning**
   - Removed missing values
   - Encoded categorical variables (Label Encoding)
2. **Exploratory Data Analysis**
   - Summary statistics
   - Count plots for final results
   - Correlation heatmaps
3. **Machine Learning**
   - Random Forest classifier
   - Train/test split (80/20)
   - Model trained to predict `final_result`
4. **Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

### 🔑 Model Accuracy:
> Achieved approximately **XX% accuracy** (update based on your output)

---

## 📊 Power BI Dashboard Summary (`Student_Performance.pbix`)

**Dashboards Created:**
- Final Result distribution by:
  - Gender
  - Age Band
  - Region
  - Highest Education
  - Disability status
- Filters (Slicers) for deep drill-down
- Interactive visuals showing relationships between features

Power BI helps reveal how demographics influence academic success and dropout patterns.

---

## 🧠 Key Insights

- Students with higher prior education levels tend to perform better.
- Students with disabilities and from lower IMD bands show increased risk of failure or withdrawal.
- Age and gender also play significant roles in final outcomes.
- The predictive model can help flag at-risk students early.

---

## 🚀 How to Run This Project

### Python Notebook
1. Clone the repository:
