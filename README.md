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

 
> ![Step 2](https://github.com/TanmaySingh007/Mental-Health-EDA/blob/9dbf6e5e9446fc6628cc6ea9988be4daeaa4aea6/2.png)

---

### ✅ Step 3: Visualize Treatment Rate by Country

- Bar chart of top 10 countries' treatment rates


> ![Step 3](https://github.com/TanmaySingh007/Mental-Health-EDA/blob/36801a679e2a6511a98a54e6eb90bc15ba42e92d/3.png)

---

### ✅ Step 4: Mental vs Physical Health Attitude by Country

- Analyzed responses to: _"Does your employer treat mental health as seriously as physical health?"_
- Filtered by top countries


> ![Step 4](https://github.com/TanmaySingh007/Mental-Health-EDA/blob/16c6696e2932d9e9f0ab17eac8a1489ff8610145/4.png)

---

### ✅ Step 5: Attitude Comparison Chart

- Stacked bar chart of mental vs physical health attitude comparison
  
> ![Step 5](https://github.com/TanmaySingh007/Mental-Health-EDA/blob/930acd4268bd71234e19bac2ef9cfbb910aff660/5.png)

---

### ✅ Step 6: Binary Encoding of Mental Health Factors

- Mapped all key survey responses to numeric (Yes = 1, No = 0, Maybe = 0.5)
- Prepared for correlation analysis

 
> ![Step 6](https://github.com/TanmaySingh007/Mental-Health-EDA/blob/148cf9167c74817c289c31daa6ebe8189dbf923c/6.png)

---

### ✅ Step 7: Correlation Analysis

- Found strongest predictors of mental health treatment:
  - Family history
  - Mental health benefits
  - Anonymity
  - Supervisor/coworker support
 
> ![Step 7](https://github.com/TanmaySingh007/Mental-Health-EDA/blob/531dc19eb5aca1a7ce1de3639ade34f35fb1ad5d/7.png)

---

### ✅ Step 8: Visualize Correlation

- Horizontal bar plot of top 10 strongest factors related to seeking treatment

 
> ![Step 8](https://github.com/TanmaySingh007/Mental-Health-EDA/blob/64e99d2509ec8b899e7c6270a06d6b41e2404c8b/8.png)

---

## 🔍 Deep-Dive Demographic Analysis

---

### ✅ Step 9: Treatment Rate by Gender

- Compared proportions of men, women, and others seeking treatment

> ![Step 9](https://github.com/TanmaySingh007/Mental-Health-EDA/blob/18e307a7eebc5ffad9bf8cb9180e49b0b890ef53/9.png)

---

### ✅ Step 10: Work Interference by Gender

- Explored how different genders reported mental health interfering with work

> ![Step 10](https://github.com/TanmaySingh007/Mental-Health-EDA/blob/3e724b5e37548507d9bab64ad1d1ac9886dab64f/10.png)

---

### ✅ Step 11: Treatment by Company Size

- Found trends in mental health support based on company size

  
> ![Step 11](https://github.com/TanmaySingh007/Mental-Health-EDA/blob/d6da94908defe571d5fba0e6bfc7017a9f5db8b2/11.png)

---

### ✅ Step 12: Treatment by Remote Work

- Compared remote vs on-site workers in terms of seeking help


> ![Step 12](https://github.com/TanmaySingh007/Mental-Health-EDA/blob/50be451dbadc2e27b6f714b391b0ae29807b3a72/12.png)

---

### ✅ Step 13: Tech vs Non-Tech Companies

- Analyzed if tech companies were more supportive of mental health treatment

 
> ![Step 13](https://github.com/TanmaySingh007/Mental-Health-EDA/blob/2b287acb9ae12e98801371ab1f66fe2085dc12da/13.png)

---

### ✅ Step 14: Heatmap – Gender vs Company Size

- Created a heatmap showing the interaction between **gender** and **company size** in treatment rates
  
> ![Step 14](https://github.com/TanmaySingh007/Mental-Health-EDA/blob/3fc504c06274b4f53e3d820e654d4afe2f3c6d99/14.png)

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
