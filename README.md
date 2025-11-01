# Eda-project
# 👨‍💼 Employee Attrition Analysis

This project focuses on analyzing employee attrition using a real-world employee dataset.  
The goal is to clean the dataset, explore employee behavior, and identify early insights into why employees may leave the company.

---

## 📌 Project Workflow

### 🔹 1️⃣ Data Loading
The dataset (`employee_attrition_classification.csv`) is imported and inspected for structure, missing values, and inconsistencies.

### 🔹 2️⃣ Data Cleaning & Preprocessing
We perform the following cleaning operations:
- Remove duplicate entries
- Fix inconsistent category values (e.g., department names, education levels)
- Convert incorrect data types
- Replace missing values **individually** for each column
- Handle outliers and invalid numeric entries (negative values, etc.)

✅ After cleaning, the dataset becomes consistent and ready for analysis.

### 🔹 3️⃣ Exploratory Data Analysis (EDA)
Various charts are used to understand:
- Employee attrition count (Who left vs who stayed)
- Salary distribution and unusual salary values
- Department distribution and sizes
- Education level proportions
- Relationship between salary and years at company

📊 Visualizations include:
- Bar Charts
- Pie Charts
- Histograms
- Scatter Plots
- Box Plots

---

## 📊 Key Observations ✅
- A noticeable number of employees have left the company → **Retention issue**
- Salary distribution varies widely across departments
- Higher salaried employees tend to stay longer in the company
- Bachelor’s and Ph.D. are the most common education levels
- Some departments have a much higher employee count than others

These insights help in identifying possible factors contributing to attrition.

---

## 📂 Dataset Description

| Column | Description |
|--------|-------------|
| department | Employee department |
| work_accident | Any work accident reported |
| emp_id | Unique employee ID |
| left_company | Attrition status (Yes/No) |
| salary_k | Salary in thousands |
| education_level | Education qualification |
| promotion_last_5years | Promotion history |
| years_at_company | Experience duration |
| last_performance_score | Final performance score |

---

## ▶️ How to Run the Notebook
1. Upload the notebook to **Google Colab** (recommended)
2. Upload the dataset to the same runtime directory
3. Install required libraries (if missing):
   ```bash
   pip install pandas numpy matplotlib seaborn
