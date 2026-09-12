# HR Employee Attrition Analysis — Excel

## 📌 Project Overview

This project analyzes employee attrition using the IBM HR Employee Attrition dataset.

The objective is to identify patterns and factors associated with employee turnover and provide business insights that could help HR teams improve employee retention.

The analysis was performed entirely in **Microsoft Excel** using formulas, PivotTables, charts, and an interactive-style dashboard.

---

## 🎯 Business Questions

The project focuses on the following questions:

1. What is the overall employee attrition rate?
2. Which department has the highest attrition?
3. Which job role has the highest attrition?
4. Does overtime affect employee attrition?
5. Does salary level relate to attrition?
6. Does employee tenure relate to attrition?
7. Does job satisfaction relate to attrition?

---

## 🛠️ Tools & Skills Used

* **Microsoft Excel**
* Data Cleaning
* Excel Formulas
* `COUNTIF` / `COUNTA`
* PivotTables
* PivotCharts
* Data Visualization
* KPI Creation
* Dashboard Design
* Business Analysis
* Problem Solving & Critical Thinking

---

## 🔍 Data Cleaning

Before performing the analysis, the dataset was checked for:

* Duplicate employees
* Missing values
* Constant columns
* Data consistency
* Unusual or invalid values

### Data Quality Findings

* No duplicate employees were identified.
* No blank values were identified in the analyzed data.
* `EmployeeCount`, `Over18`, and `StandardHours` contained only one unique value and were excluded from analytical comparisons.

The original dataset was preserved as the **Raw Data** sheet.

---

## 📊 Analysis Performed

### 1. Overall Attrition

The overall attrition rate was calculated by comparing the number of employees who left with the total number of employees.

**Overall Attrition Rate: 16.12%**

---

### 2. Attrition by Department

Attrition rates were compared across:

* Sales
* Human Resources
* Research & Development

**Key finding:** Sales had the highest attrition rate among the departments.

---

### 3. Attrition by Job Role

Employee attrition was analyzed across different job roles.

**Key finding:** Sales Representatives had one of the highest attrition rates among the job roles analyzed.

---

### 4. Overtime and Attrition

Attrition was compared between employees who worked overtime and those who did not.

**Key finding:** Employees working overtime had a substantially higher attrition rate than employees who did not work overtime.

---

### 5. Salary and Attrition

Employees were grouped into salary bands and their attrition rates were compared.

This analysis was used to identify whether attrition patterns differed across salary levels.

---

### 6. Tenure and Attrition

Employees were grouped based on their years at the company.

Tenure bands were used to identify whether employees at different stages of their careers experienced different attrition rates.

---

### 7. Job Satisfaction and Attrition

Attrition rates were compared across job satisfaction levels.

**Key finding:** Employees with lower job satisfaction showed higher attrition rates than employees with higher job satisfaction.

---

## 💡 Key Business Insights

The analysis indicates that employee attrition varies across several employee characteristics.

The major areas identified for further investigation include:

* Overtime
* Job role
* Department
* Job satisfaction
* Salary
* Employee tenure

Employees working overtime and employees in certain high-attrition roles appear to be particularly important groups for HR to investigate.

These findings indicate **associations rather than causation**. Further analysis would be required to determine whether these factors directly cause employee attrition.

---

## 📈 Dashboard

The project includes an Excel dashboard containing:

* Total Employees
* Employees Who Left
* Employees Who Stayed
* Overall Attrition Rate
* Attrition by Department
* Attrition by Job Role
* Attrition by Overtime
* Attrition by Job Satisfaction
* Key Business Findings

---

## 📁 Project Structure

```text
HR-Employee-Attrition-Analysis/
│
├── README.md
│
├── HR_Employee_Attrition_Analysis.xlsx
│
└── screenshots/
    ├── dashboard.png
    └── analysis.png
```

---

## 📚 Dataset

The project uses the **IBM HR Employee Attrition dataset**, which contains employee demographic, job, compensation, satisfaction, and attrition information.

The dataset is commonly used for practicing HR analytics and employee attrition analysis.

---

## 🚀 Future Improvements

Possible next steps for this project include:

* Build the analysis in **SQL**
* Recreate the dashboard in **Power BI**
* Perform statistical analysis using **Python**
* Build an employee attrition prediction model
* Analyze relationships between multiple factors simultaneously
* Develop an HR retention strategy based on the findings

---

## 👤 Author

**sanjay**

Aspiring Data Analyst | Excel | SQL | Power BI | Python

---

⭐ If you found this project useful, feel free to explore the workbook and analysis.
# HR-employee-attrition-analysis
