# HR Analytics Project

## 📚 Table of Content

- [Project Overview](#project-overview)  
- [Data Sources](#data-sources)  
- [Tools and Technologies Used](#tools-and-technologies-used)  
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)  
- [Exploratory Data Analysis](#exploratory-data-analysis)  
- [Data Analysis](#data-analysis)  
- [Results / Findings](#results--findings)  
- [Recommendations](#recommendations)  
- [Limitations](#limitations)  
- [References](#references)  

---

## 🧾 Project Overview

This project involves the analysis of HR data to provide insights into employee demographics, satisfaction, recruitment channels, performance metrics, and workforce trends. Using Power BI, I created an interactive dashboard to support HR teams in making strategic, data-driven decisions regarding workforce planning and employee retention.

---

## 🗂️ Data Sources

- **Primary Source**: `HRData_Dummy.xlsx` — A synthetic dataset generated to replicate real-world HR records.
- **Data Fields**:
  - Employee ID, Gender, Department, State, Marital Status
  - Recruitment Source, Satisfaction, Performance Score
  - Salary, Status (Active/Terminated), Hire Date

  ---

  ## 🛠️ Tools and Technologies Used

- **Power BI** — For data visualization and dashboard creation  
- **Microsoft Excel** — For initial data formatting and preprocessing  
- **DAX (Data Analysis Expressions)** — For creating calculated measures and KPIs  
- *(Optional)* Python (Pandas) — For synthetic dataset generation

---

## 🧹 Data Cleaning and Preparation

- Removed duplicate records and standardized column headers
- Converted `HireDate` to datetime format
- Created calculated fields such as:
  - Employee tenure
  - Hiring year
- Encoded satisfaction and performance scores for visual sorting
- Ensured no null or missing values in critical columns

---

## 📊 Exploratory Data Analysis

Initial EDA revealed:
- Majority of employees are **female (≈57%)**
- High representation from **Production** and **Sales** departments
- Most hires occurred between **2010 and 2015**
- Recruitment primarily via **Indeed** and **Google Search**
- Employee satisfaction skewed toward **High and Very High**

## 📈 Data Analysis

Key calculated metrics and insights:
- **Headcount distribution** by gender, status, department
- **Performance score analysis** by recruitment source and department
- **Satisfaction levels** segmented by marital status, gender, and state
- **Termination trends** by year and department
- **Salary distribution** across performance groups and departments

---

## ✅ Results / Findings

- **44%** of employees are married, suggesting family-oriented policies could improve retention.
- **Production department** has the highest number of terminations.
- Employees hired via **Indeed** tend to have better performance ratings.
- Satisfaction and performance are positively correlated in most departments.
- Some locations (e.g., TX, FL) have higher termination rates and lower satisfaction scores.

---

## 💡 Recommendations

1. **Invest more in effective recruitment channels** like Indeed and Google Search.
2. **Launch engagement programs** for Production department employees.
3. **Analyze exit interviews** from high-termination states to identify root causes.
4. Consider **compensation reviews** for departments with low satisfaction but high performance.
5. Monitor and support employees in early tenure (<2 years), as they're more likely to leave.

---

## ⚠️ Limitations

- The dataset is synthetic; actual business insights would depend on real data.
- No post-termination feedback data was included to support retention strategy.
- Absence of fields like age, education level, or job title limits deeper analysis.
- No time-series data for promotions, appraisals, or internal transfers.

---

## 🔍 References

- Dataset inspired by publicly available HR analytics schemas  
- Power BI documentation: [https://docs.microsoft.com/en-us/power-bi/](https://docs.microsoft.com/en-us/power-bi/)  
- DAX Guide: [https://dax.guide](https://dax.guide)  
- SHRM HR Analytics Best Practices: [https://www.shrm.org/](https://www.shrm.org/)



