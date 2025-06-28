# 🧠 Mental Health in Tech – Exploratory Data Analysis (EDA)

This project explores the 2014 Mental Health in Tech survey dataset to understand the frequency of mental health issues and how workplace attitudes and policies affect them. Using `pandas`, `matplotlib`, and `seaborn`, we analyze how demographics, geography, company type, and size influence mental health treatment.

---

## 📁 Dataset Overview

The dataset includes 1,200+ responses and covers:

- **Demographics**: Age, Gender, Country, State
- **Employment**: Company size, Remote work, Tech affiliation
- **Mental Health**: Family history, Treatment, Interference with work, Benefits, Attitudes

---

## ⚙️ Tools Used
- Python 3
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 EDA Steps & Analysis

---

### ✅ Step 1: Data Cleaning & Gender Normalization

- Filtered out unrealistic ages
- Normalized gender values into **Male**, **Female**, and **Other**

> _EDA Step by step  Screenshot_:  
> ![Step 1](https://github.com/TanmaySingh007/Mental-Health-EDA/blob/80974f827baea038ae0ad5e676090667eece0359/1.png)

---

### ✅ Step 2: Treatment Frequency by Country

- Computed the percentage of people seeking treatment per country
- Selected top 10 countries with highest treatment rates

> _Optional Screenshot_:  
> ![Step 2](screenshots/step2_treatment_country.png)

---

### ✅ Step 3: Visualize Treatment Rate by Country

- Bar chart of top 10 countries' treatment rates

> _Optional Screenshot_:  
> ![Step 3](screenshots/step3_country_bar.png)

---

### ✅ Step 4: Mental vs Physical Health Attitude by Country

- Analyzed responses to: _"Does your employer treat mental health as seriously as physical health?"_
- Filtered by top countries

> _Optional Screenshot_:  
> ![Step 4](screenshots/step4_attitudes.png)

---

### ✅ Step 5: Attitude Comparison Chart

- Stacked bar chart of mental vs physical health attitude comparison

> _Optional Screenshot_:  
> ![Step 5](screenshots/step5_attitude_chart.png)

---

### ✅ Step 6: Binary Encoding of Mental Health Factors

- Mapped all key survey responses to numeric (Yes = 1, No = 0, Maybe = 0.5)
- Prepared for correlation analysis

> _Optional Screenshot_:  
> ![Step 6](screenshots/step6_binary_map.png)

---

### ✅ Step 7: Correlation Analysis

- Found strongest predictors of mental health treatment:
  - Family history
  - Mental health benefits
  - Anonymity
  - Supervisor/coworker support

> _Optional Screenshot_:  
> ![Step 7](screenshots/step7_correlations.png)

---

### ✅ Step 8: Visualize Correlation

- Horizontal bar plot of top 10 strongest factors related to seeking treatment

> _Optional Screenshot_:  
> ![Step 8](screenshots/step8_corr_plot.png)

---

## 🔍 Deep-Dive Demographic Analysis

---

### ✅ Step 9: Treatment Rate by Gender

- Compared proportions of men, women, and others seeking treatment

> _Optional Screenshot_:  
> ![Step 9](screenshots/step9_gender.png)

---

### ✅ Step 10: Work Interference by Gender

- Explored how different genders reported mental health interfering with work

> _Optional Screenshot_:  
> ![Step 10](screenshots/step10_work_interfere.png)

---

### ✅ Step 11: Treatment by Company Size

- Found trends in mental health support based on company size

> _Optional Screenshot_:  
> ![Step 11](screenshots/step11_company_size.png)

---

### ✅ Step 12: Treatment by Remote Work

- Compared remote vs on-site workers in terms of seeking help

> _Optional Screenshot_:  
> ![Step 12](screenshots/step12_remote.png)

---

### ✅ Step 13: Tech vs Non-Tech Companies

- Analyzed if tech companies were more supportive of mental health treatment

> _Optional Screenshot_:  
> ![Step 13](screenshots/step13_tech_nontech.png)

---

### ✅ Step 14: Heatmap – Gender vs Company Size

- Created a heatmap showing the interaction between **gender** and **company size** in treatment rates

> _Optional Screenshot_:  
> ![Step 14](screenshots/step14_heatmap.png)

---

## 📦 Output

All EDA tables are exported to:  
**📄 `Mental_Health_EDA_Report.xlsx`**

---

## 📝 Conclusion

This project highlights how workplace support systems, employee demographics, and company culture significantly influence the likelihood of seeking treatment for mental health. Future extensions may include ML modeling or interactive dashboards.

---

## 🙌 Contributions

Feel free to fork this repo and add:
- More visualizations
- Dashboard integration (e.g., Streamlit or Power BI)
- 2016 survey comparison

---

## 📎 References

- [Original Dataset - OSMI 2014](https://osmihelp.org/research)
