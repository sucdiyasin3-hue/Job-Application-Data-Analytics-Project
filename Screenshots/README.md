# Job Application Data Analytics Project

## 📊 Project Overview

This project analyzes a Job Application Dataset using Microsoft Excel. 
The analysis follows a complete data analytics workflow:

**Raw Data → Data Cleaning → Data Analysis → PivotTables → Charts → KPIs → Slicers → Dashboard → Interpretation**

The main objective is to clean the job application data, analyze applicant characteristics and application outcomes, and present meaningful insights through an interactive Excel dashboard.

---

## 📁 Dataset Information

- **Dataset:** Job Application Data
- **Total Applicants:** 293
- **Software Used:** Microsoft Excel

### Main Variables

- Applicant ID
- Application Date
- Department
- Experience Years
- Education Level
- Interview Score
- Application Status
- Interview Performance
- Application Year
- Application Month
- Application Day

---

## 🧹 Data Cleaning

The original dataset contained several data-quality issues, including:

- Missing values
- Blank cells
- Duplicate records
- NULL values
- N/A values
- Underscores (_)
- Invalid values
- Inconsistent text formatting

### Text Cleaning

Text-cleaning techniques were applied to standardize categorical data.

The following Excel functions were used:

- **TRIM** – removed unnecessary spaces.
- **PROPER** – standardized text capitalization.
- **UPPER** – converted text into uppercase format.

For example, department values such as different capitalization formats were standardized to improve consistency and make analysis more reliable.

---

## 📈 Data Analysis

Excel formulas and functions were used to calculate and analyze the dataset.

### Functions Used

- SUM
- AVERAGE
- COUNT
- MIN
- MAX
- COUNTIF
- SUMIF
- AVERAGEIF
- IF

These functions helped calculate applicant counts, average experience, interview scores, and application-status statistics.

---

# 📊 Data Interpretation

## 1. Application Status Analysis

The application-status analysis shows the following distribution:

| Status | Applicants |
|---|---:|
| Hired | 85 |
| Pending | 64 |
| Rejected | 73 |
| Shortlisted | 71 |
| **Total** | **293** |

### Interpretation

The largest group is **Hired**, with 85 applicants. This represents approximately 29% of the total applicants.

There are 73 rejected applicants, while 71 applicants were shortlisted and 64 remained pending.

Overall, the results show that applicants were distributed across all four application outcomes, with **Hired** being the largest category.

---

## 2. Application Status by Department

The PivotTable and chart show differences in application outcomes across departments.

### Interpretation

- **Sales** has the highest number of hired applicants, with **21**.
- **Finance** follows with **16 hired applicants**.
- **Administration** and **IT** each have **13 hired applicants**.
- **HR** has **7 hired applicants**.
- **Unknown** has the lowest number of hired applicants, with **4**.

The results indicate that application outcomes vary by department. Sales has the largest overall number of applicants, while the Unknown category has the smallest.

---

## 3. Average Experience Years by Department

The average experience analysis shows:

| Department | Average Experience |
|---|---:|
| Sales | 8.5 years |
| Unknown | 7.7 years |
| Operations | 7.6 years |
| HR | 7.5 years |
| Finance | 7.4 years |
| IT | 7.4 years |
| Administration | 6.8 years |

### Interpretation

**Sales** has the highest average applicant experience at **8.5 years**.

**Administration** has the lowest average experience at **6.8 years**.

The overall average experience across the dataset is **7.5 years**.

This suggests that applicants in Sales generally have more years of experience than applicants in the other departments represented in the dataset.

---

## 4. Total Interview Score by Department

The total interview score varies considerably between departments.

| Department | Total Interview Score |
|---|---:|
| Sales | 3,627.6 |
| Finance | 3,992.7 |
| IT | 3,546.2 |
| Administration | 3,261.2 |
| Operations | 2,929.1 |
| HR | 2,916.3 |
| Unknown | 1,092.2 |

### Interpretation

**Finance** has the highest total interview score at **3,992.7**, followed by Sales at **3,627.6**.

The **Unknown** department has the lowest total interview score at **1,092.2**, which is consistent with it having fewer applicants.

The total interview score is influenced by the number of applicants in each department as well as their individual interview scores, so it should not be interpreted as average performance.

---

## 5. Application Status Distribution

The dashboard visualizes the distribution of application statuses.

- **Hired:** approximately 29%
- **Rejected:** approximately 25%
- **Shortlisted:** approximately 24%
- **Pending:** approximately 22%

### Interpretation

The dashboard shows that **Hired applicants form the largest proportion** of the dataset.

Rejected and shortlisted applicants represent similar proportions, while Pending applicants represent the smallest proportion.

---

# 📊 Interactive Dashboard Interpretation

The final dashboard combines the major findings into one interactive view.

### KPI Cards

The dashboard contains four main KPIs:

- **Total Applicants:** 293
- **Hired Applicants:** 85
- **Average Experience:** 7.5 years
- **Average Interview Score:** 72.9

### Interactive Filters

The dashboard includes slicers for:

- Department
- Application Status
- Education Level

These slicers allow users to filter the dashboard and explore specific groups of applicants.

---

# 🔍 Key Findings

Based on the analysis:

1. The dataset contains **293 applicants**.
2. **85 applicants were hired**, making Hired the largest application-status category.
3. The overall average experience is **7.5 years**.
4. The overall average interview score is **72.9**.
5. **Sales** has the highest average applicant experience at **8.5 years**.
6. **Administration** has the lowest average experience at **6.8 years**.
7. **Finance** has the highest total interview score at **3,992.7**.
8. Application outcomes vary across departments.
9. The dashboard allows users to explore the results interactively using slicers.

---

# 🎯 Conclusion

This project demonstrates how Microsoft Excel can be used to perform a complete data analytics workflow.

The project started with raw job application data, identified data-quality problems, applied cleaning and standardization techniques, and then used Excel formulas, PivotTables, charts, KPIs, and slicers to transform the data into useful information.

The final interactive dashboard provides a clear overview of applicant volume, hiring outcomes, experience levels, and interview performance.

The analysis can help users understand patterns in the recruitment dataset and compare application outcomes across different departments and applicant groups.

---

## 🛠️ Tools & Techniques

- Microsoft Excel
- Data Cleaning
- Text Functions
- Excel Formulas
- PivotTables
- PivotCharts
- KPI Cards
- Slicers
- Interactive Dashboard
- Data Interpretation

---

## 👩‍🎓 Author

**Sucdi Yasin Husein**

**Course:** Excel for Data Scientist

**Project:** Job Application Data Analytics Project
