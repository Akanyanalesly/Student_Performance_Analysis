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
  
     <img width="390" height="281" alt="Image" src="https://github.com/user-attachments/assets/5b57b74f-c548-41ee-9f8f-e2c3e594f653" />

     <img width="419" height="211" alt="Image" src="https://github.com/user-attachments/assets/59efffea-d8ef-44d3-89f1-4c8f8adde146" />
     
2. **Exploratory Data Analysis**
   - Summary statistics
   - Count plots for final results
   - Correlation heatmaps
  <img width="461" height="287" alt="Image" src="https://github.com/user-attachments/assets/f332ca2f-aefa-48f8-828c-3020b5ead10f" />

  <img width="548" height="253" alt="Image" src="https://github.com/user-attachments/assets/6419cae2-9838-40ca-be3d-c92a27dbfca0" />

  <img width="550" height="350" alt="Image" src="https://github.com/user-attachments/assets/77ad3b08-9be4-4d87-859c-7b2a6a5c9c1b" />
     
3. **Machine Learning**
   - Random Forest classifier
   - Train/test split (80/20)
   - Model trained to predict `final_result`
  
     <img width="338" height="58" alt="Image" src="https://github.com/user-attachments/assets/d7e6b869-a806-43de-b22d-4af04a759d7c" />

     <img width="524" height="350" alt="Image" src="https://github.com/user-attachments/assets/aef4fc16-0bd5-45ad-bc92-57acce0d0d90" />
     
4. **Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
  
     <img width="502" height="369" alt="Image" src="https://github.com/user-attachments/assets/a5564a90-4cb6-4702-a528-91d5d3f8dee2" />
  
     

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

<img width="514" height="303" alt="Image" src="https://github.com/user-attachments/assets/027ffcc8-6f19-47bd-945c-7e4dc921f111" />

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
