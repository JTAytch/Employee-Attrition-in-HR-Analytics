# 📊 Predicting Employee Attrition in HR Analytics

**Team:** Eliana Alon | Lauren Furman | Joseph Aytch | Michelle Valencia  
**Dataset:** [HR Analytics Prediction – Kaggle](https://www.kaggle.com/datasets/rishikeshkonapure/hr-analytics-prediction)  
**Goal:** Identify key factors influencing employee attrition and build predictive models to support targeted retention strategies.

---

## 📌 Project Overview

Employee attrition is a costly challenge for organizations. This project analyzes a public HR dataset containing demographic, job satisfaction, and organizational attributes to:

- Understand **why employees leave**.
- Predict **which employees are at risk**.
- Recommend **data‑driven retention strategies**.

We combine **exploratory data analysis**, **statistical testing**, and **machine learning models** to uncover actionable insights for HR decision‑makers.

---

## 🎯 Research Questions

1. What are the primary factors that predict employee attrition?  
2. How does job satisfaction influence an employee’s decision to stay or leave?  
3. What role do demographic variables (e.g., age, education level) play in attrition rates?  
4. Can machine learning models effectively predict which employees are likely to leave?  
5. How can results inform HR departments to improve retention strategies?

---

## 📂 Dataset Details

**Source:** Public HR dataset from Kaggle  
**Key Fields:**
- `Age` – Employee age  
- `Education` – Highest education level attained  
- `Department` – Department of employment  
- `JobRole` – Specific role within the company  
- `MonthlyIncome` – Monthly salary  
- `YearsAtCompany` – Tenure at the organization  
- `JobSatisfaction` – Self‑reported satisfaction level  
- `WorkLifeBalance` – Employee rating of work‑life balance  
- `Overtime` – Whether the employee works overtime  
- `Attrition` – Target variable (Yes/No)

---

## 🛠 Methodology

### **1. Data Preprocessing**
- Handle missing values, remove duplicates, ensure consistency.
- Encode categorical variables and standardize numerical features.
- Normalize data for uniform scaling.

### **2. Exploratory Data Analysis (EDA)**
- Descriptive statistics for all features.
- Visualizations: histograms, box plots, scatter plots.
- Identify trends and correlations (e.g., job level vs. income, age vs. attrition).

### **3. Statistical Analysis**
- Correlation analysis to detect relationships between variables.
- Hypothesis testing to validate significant findings.

### **4. Predictive Modeling**
- Algorithms: Logistic Regression, Decision Trees, and others.
- Model evaluation using accuracy, precision, recall, and F1‑score.

### **5. Clustering**
- K‑Means segmentation to group employees by attrition risk.

---

## 📈 Key Insights (from EDA)

- **Age & Attrition:** Peak attrition between ages 30–35; lower rates after 35.  
- **Tenure:** Highest attrition in the first year; notable spikes at ~2.5 and ~7 years with current manager.  
- **Experience:** Employees with 0–2 years of total work experience are more likely to leave; stability increases after ~8 years.  
- **Job Level & Income:** Strong positive correlation — higher levels earn more and tend to stay longer.  
- **Manager Relationship:** Longer tenure with the same manager generally correlates with lower attrition.

---

## 💡 Potential Benefits

- **Enhanced Retention:** Identify and address key attrition drivers.  
- **Targeted Strategies:** Tailor interventions to high‑risk groups.  
- **Informed Decisions:** Use predictive insights for proactive HR planning.  
- **Improved Satisfaction:** Foster a positive work environment.  
- **Efficient Resource Allocation:** Focus retention efforts where they have the most impact.

---

## ⚖️ Ethical Considerations

- **Data Privacy:** All data anonymized; no personal identifiers.  
- **Bias Mitigation:** Avoid discriminatory practices in model design.  
- **Transparency:** Clearly communicate model limitations and avoid over‑reliance on predictions.

---

## 📌 Potential Issues & Limitations

- **Data Quality:** Missing or inconsistent records.  
- **Bias:** Sampling or response bias in survey data.  
- **Interpretation:** Correlation ≠ causation; external factors may influence results.  
- **Generalizability:** Findings may be dataset‑specific.

---

## 📅 Project Timeline

- **Fall 2024:** Data exploration, EDA, and initial modeling.  
- **Next Steps:** Model refinement, feature importance analysis, and actionable HR recommendations.

---

## 📎 References

- [IBM HR Analytics Dataset – Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)  
- [Employee Attrition Dataset – Kaggle](https://www.kaggle.com/datasets/tejashvi14/employee-attrition-dataset)  
- [HR Analytics Prediction – Kaggle](https://www.kaggle.com/datasets/rishikeshkonapure/hr-analytics-prediction)  
- Academic and industry literature on employee turnover, engagement, and retention strategies.

---
