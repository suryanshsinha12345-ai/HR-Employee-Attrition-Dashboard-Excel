# 📊 HR Employee Attrition Dashboard | Excel

## 📌 Project Overview

The **HR Employee Attrition Dashboard** is an interactive Excel-based HR analytics project focused on understanding employee attrition and identifying factors associated with employees leaving an organization.

The project uses employee-level HR data to perform data cleaning, quality checks, pivot-based analysis, and dashboard development.

The final dashboard provides an executive overview of employee attrition across areas such as department, gender, overtime, job satisfaction, monthly income, distance from work, and years at the company.

<img width="1078" height="494" alt="image" src="https://github.com/user-attachments/assets/c9a7a6ed-eff5-4429-97bc-c5d37edd3e4d" />

---

## 🎯 Business Objective

Employee attrition can significantly impact recruitment costs, workforce productivity, and organizational performance.

The objective of this project is to analyze employee attrition and identify patterns that may help HR teams understand:

- Overall employee attrition
- Attrition across departments
- Gender-wise attrition
- Attrition based on overtime
- Employee satisfaction across job roles
- Monthly income differences between employees who stayed and those who left
- Relationship between distance from work and attrition
- Performance rating distribution
- Years spent at the company for employees who stayed versus employees who left
- Age characteristics of employees who left

---

## 📂 Dataset

The project uses an HR employee dataset containing **1,471 rows and 35 columns** in the original worksheet.

The workbook includes a cleaned dataset and multiple analytical worksheets for different HR dimensions.

### Key fields analyzed include:

- Age
- Attrition
- Department
- Gender
- Job Role
- Job Satisfaction
- Monthly Income
- Distance From Home
- OverTime
- Performance Rating
- Years At Company

---

## 🧹 Data Preparation

The workbook includes dedicated sheets for data preparation and quality checking.

### Data Cleaning

A separate **Clean data** worksheet was created to prepare the dataset for analysis.

### Data Quality Checks

The project also includes a **Data Quality** worksheet to check for null values in important fields, including:

- Age
- Attrition
- Department
- Monthly Income
- Job Role
- OverTime

This helps ensure that the data used for analysis is complete and reliable.

---

## 📊 Analysis Performed

### 1. Attrition by Department

Employee attrition was analyzed across:

- Human Resources
- Research & Development
- Sales

This helps identify departments with relatively higher employee turnover.

---

### 2. Attrition by Gender

The analysis compares employees who stayed and employees who left across:

- Female employees
- Male employees

The dataset contains:

| Gender | Stayed | Left | Total |
|---|---:|---:|---:|
| Female | 501 | 87 | 588 |
| Male | 732 | 150 | 882 |

---

### 3. Attrition by Age

The analysis calculates the average age of employees who left the organization.

**Average age of employees who left: 33.61 years**

---

### 4. Job Satisfaction Analysis

Average job satisfaction was analyzed across different job roles.

Roles included in the analysis include:

- Healthcare Representative
- Research Scientist
- Sales Executive
- Sales Representative
- Manager
- Research Director
- Laboratory Technician
- Manufacturing Director
- Human Resources

The overall average job satisfaction among the analyzed employee group is approximately **2.73**.

---

### 5. Monthly Income Analysis

Monthly income was compared between employees who stayed and employees who left.

| Employee Group | Average Monthly Income |
|---|---:|
| Overall | 6,502.93 |
| Employees Who Left | 4,787.09 |

This analysis helps explore whether compensation levels differ between employees who remain with the organization and those who leave.

---

### 6. Distance From Home Analysis

Employee attrition was analyzed across different distance groups:

- 0–5 km
- 6–10 km
- 11–20 km
- 21+ km

The analysis shows the following attrition rates:

| Distance Group | Attrition Rate |
|---|---:|
| 0–5 km | 14% |
| 6–10 km | 14% |
| 11–20 km | 20% |
| 21+ km | 22% |

This provides an opportunity to investigate whether longer commuting distances are associated with higher attrition.

---

### 7. Overtime Analysis

Attrition was compared between employees who worked overtime and those who did not.

| Overtime | Stayed | Left | Total |
|---|---:|---:|---:|
| No | 944 | 110 | 1,054 |
| Yes | 289 | 127 | 416 |

The analysis can be used to investigate the relationship between overtime requirements and employee attrition.

---

### 8. Performance Rating Analysis

Employee performance ratings were analyzed to understand the distribution of performance scores.

The dataset contains:

| Performance Rating | Employee Count |
|---|---:|
| 3 | 1,244 |
| 4 | 226 |

---

### 9. Years at Company Analysis

Average tenure was compared between employees who stayed and employees who left.

| Employee Group | Average Years at Company |
|---|---:|
| Employees Who Stayed | 7.37 |
| Employees Who Left | 5.13 |

This provides insight into the relationship between employee tenure and attrition.

---

## 📈 Dashboard

The final Excel dashboard provides an executive overview of the analysis.

### Key KPIs

- **Total Employees:** 1,470
- **Employees Left:** 237
- **Attrition Rate:** 16.12%
- **Average Age:** 33.61 years

### Dashboard Visualizations

The dashboard includes visualizations for:

- Attrition by Department
- Attrition by Gender
- Attrition Rate by Overtime
- Average Job Satisfaction by Role
- Monthly Income Comparison
- Average Years at Company

---

## 🔍 Key Insights

The analysis highlights several important patterns:

- The dataset contains **1,470 usable employee records** after accounting for the header row.
- **237 employees left**, resulting in an overall attrition rate of approximately **16.12%**.
- Employees who left had an average age of approximately **33.61 years**.
- Employees who left had a lower average monthly income (**4,787.09**) compared with the overall average (**6,502.93**).
- Employees working **overtime** show a noticeably higher number of attrition cases relative to employees who did not work overtime.
- Attrition rates increase across the distance groups, reaching **22% for employees living 21+ km away**.
- Employees who stayed had an average tenure of **7.37 years**, compared with **5.13 years** for employees who left.
- The largest department in the dataset is **Research & Development**, with 961 employees.

---

## 🛠️ Tools & Skills

### Tool

- **Microsoft Excel**

### Skills Demonstrated

- Data Cleaning
- Data Quality Checking
- Pivot Tables
- Data Analysis
- KPI Development
- Dashboard Development
- HR Analytics
- Attrition Analysis
- Data Visualization
- Business Analysis
- Excel Charts
- Comparative Analysis

---

## 💡 Business Value

This project demonstrates how Excel can be used to convert raw HR data into a structured analytical solution.

The analysis can help HR and business teams investigate potential attrition drivers such as:

- Overtime
- Compensation
- Job satisfaction
- Distance from work
- Department
- Gender
- Employee tenure
- Performance

These insights can support better employee retention strategies and workforce planning.

---

## 🚀 Future Improvements

Potential improvements to this project include:

- Adding department-wise salary analysis
- Adding attrition analysis by job role
- Creating age-group attrition analysis
- Adding a salary-band analysis
- Analyzing the relationship between job satisfaction and attrition
- Adding interactive slicers for department, gender, job role, and overtime
- Creating an attrition trend if historical data becomes available
- Developing a dedicated employee retention scorecard

<img width="466" height="501" alt="image" src="https://github.com/user-attachments/assets/c84150b5-1b7a-451c-9b34-905ec1da1f91" />


---

## 📂 Project Structure

```text
HR-Employee-Attrition-Dashboard/
│
├── HR_Employee_Attrition_Dashboard.xlsx
│
└── README.md
