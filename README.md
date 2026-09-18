# 📊 EdTech Student Placement & Learning Analytics

## 📌 Project Overview

This project analyzes **1,000 EdTech student records** to understand the factors influencing **academic performance, course completion, and placement outcomes**.

The project uses **Python, EDA, probability, confidence intervals, hypothesis testing, and correlation analysis** to generate data-driven insights.

---

## 🎯 Problem Statement

To identify the key factors related to **student performance, course completion, and placement success**, and provide actionable recommendations for an EdTech platform.

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
EDA
   ├── Non-Visual Analysis
   └── Visual Analysis
   ↓
Statistical Analysis
   ├── Probability
   ├── Confidence Intervals
   ├── Hypothesis Testing
   ├── Correlation Analysis
   └── Central Limit Theorem
   ↓
Insights & Findings
   ↓
Business Recommendations
```

---

## 🔍 Analysis Performed

### 1️⃣ Data Cleaning
- Checked missing values
- Checked duplicates
- Identified numerical & categorical variables
- Removed unnecessary columns

### 2️⃣ Exploratory Data Analysis
Analyzed:
- Student demographics
- Study hours
- Assignments
- Mock test scores
- Resume scores
- Projects
- Course completion
- Internship status
- Placement status

### 3️⃣ Statistical Analysis

| Analysis | Purpose |
|---|---|
| Probability | Measure placement & internship probabilities |
| Confidence Interval | Estimate population parameters |
| One-Sample T-Test | Compare mean score with benchmark |
| Independent T-Test | Compare two groups |
| Chi-Square Test | Test relationships between categorical variables |
| ANOVA | Compare scores across course categories |
| Pearson Correlation | Measure relationships between numerical variables |
| CLT | Demonstrate sampling distribution of means |

---

## 📊 Key Findings

- **59.2%** of students were placed.
- **34.4%** of students completed internships.
- Internship completion showed a **significant association with placement** *(p = 0.007)*.
- Study Hours and Final Score showed a **strong positive correlation** *(r = 0.809)*.
- Mock Test Score and Final Score showed a **strong positive correlation** *(r = 0.806)*.
- Resume Score and Final Score showed a **moderate positive correlation** *(r = 0.542)*.
- Paid vs Free students showed **no significant difference** in final scores *(p = 0.339)*.
- Course Category showed **no significant difference** in final scores *(p = 0.795)*.
- LinkedIn Profile showed **no statistically significant association** with placement *(p = 0.892)*.

---

## 💡 Business Insights

- Encourage students to maintain consistent study schedules.
- Increase mock-test and assessment activities.
- Provide more internship opportunities.
- Encourage project-based learning.
- Provide resume and interview preparation.
- Identify students who may need additional academic support.

---

## 🛠️ Technologies Used

**Python | Pandas | NumPy | Matplotlib | Seaborn | SciPy | Statsmodels | Jupyter Notebook**

---

## 📁 Project Structure

```text
EdTech-Student-Placement-Learning-Analytics/
│
├── EdTech_Student_Placement_Analysis.ipynb
├── dataset.csv
└── README.md
```

---

## 👨‍💻 Author

**Vempa Bhargav**  
B.Tech – Computer Science & Engineering

**Areas:** Data Analytics | Data Science | Machine Learning | Python
