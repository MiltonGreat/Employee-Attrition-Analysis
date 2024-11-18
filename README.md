# Employee Attrition Analysis

### Project Overview

This project focuses on analyzing employee attrition trends in the healthcare industry using data from the Employee Attrition for Healthcare dataset. The dataset contains detailed employee information, including demographics, job roles, satisfaction levels, and other attributes that contribute to attrition. The project uses SQL for querying the data and Python for additional analysis and visualizations.

The objective is to gain insights into employee attrition by analyzing trends across various dimensions such as department, age group, gender, job satisfaction, and business travel frequency. Predictive features from SHAP (SHapley Additive exPlanations) values are also analyzed to understand key drivers of attrition.

### Dataset

- watson_healthcare_modified.csv: Contains employee information and attrition data.
- watson_shap_values_for_testset.csv: Contains SHAP values for predictive features of attrition.

### Attributes

- Demographics: Age, Gender, MaritalStatus
- Job Role: Department, JobRole, BusinessTravel
- Satisfaction Metrics: JobSatisfaction, RelationshipSatisfaction, EnvironmentSatisfaction
- Performance and Compensation: PerformanceRating, MonthlyIncome, PercentSalaryHike
- Work-Life Metrics: WorkLifeBalance, YearsAtCompany, YearsInCurrentRole
- Target: Attrition (Yes/No)
- Rows: 1,676 employees
- Columns: 35

### Analysis Workflow

#### 1. Data Extraction and Loading

#### 2. SQL Queries

- Attrition rates by department.
- Attrition trends across gender and age groups.
- Analysis of job satisfaction levels and business travel patterns.
- Identification of top predictive features for attrition using SHAP values.

### Visualizations

- Bar charts for attrition rates by department, gender, and job satisfaction.
- Line charts for trends such as attrition over years.

### Key Findings

- Departments with higher attrition rates highlight areas requiring improved employee engagement.
- Younger employees (under 30) exhibit higher attrition rates.
- Employees with lower job satisfaction tend to leave more frequently.

### Future Work

- Build predictive models for attrition using machine learning.
- Integrate dashboards for real-time attrition insights.
- Explore additional datasets for broader analysis.

### Source

https://www.kaggle.com/datasets/jpmiller/employee-attrition-for-healthcare
