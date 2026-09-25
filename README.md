# Exploratory Data Analysis of Employee Attrition

## Thiranex Data Science Internship – Task 3

**Author:** Sai Santhana Lakshmi S

---

## Project Overview

This project performs Exploratory Data Analysis (EDA) on an employee
attrition dataset to understand employee characteristics, identify
patterns, and analyze relationships between different features and
employee attrition.

The analysis follows a structured EDA workflow including data
understanding, statistical analysis, visualization, feature
relationships, correlation analysis, and key findings.

---

## Dataset

The dataset contains **100 employee records** with the following
features:

- Age
- Monthly Income
- Job Satisfaction
- Years at Company
- Overtime
- Work-Life Balance
- Job Level
- Attrition

### Target Variable

- `0` = Stayed
- `1` = Left

---

## EDA Workflow

### 1. Data Understanding

The dataset was examined for:

- Number of rows and columns
- Data types
- Statistical summary
- Missing values
- Duplicate records

The dataset contains **100 records and 8 features**.

The dataset was checked and found to contain **no missing values and
no duplicate records**.

---

### 2. Statistical Analysis

The following statistical measures were analyzed:

- Mean
- Median
- Standard deviation
- Minimum value
- Maximum value

These statistical measures were used to understand the distribution
and characteristics of the numerical features.

---

### 3. Data Visualization

The following visualizations were created:

- Age Distribution
- Monthly Income Distribution
- Job Satisfaction Distribution
- Employee Attrition Distribution
- Attrition by Overtime
- Attrition by Job Satisfaction
- Years at Company vs Attrition
- Monthly Income vs Attrition
- Correlation Heatmap
- Attrition Rate by Overtime

These visualizations help identify patterns, distributions, and
differences within the employee dataset.

---

### 4. Feature Relationships

Different employee characteristics were compared with attrition,
including:

- Overtime and Attrition
- Job Satisfaction and Attrition
- Years at Company and Attrition
- Monthly Income and Attrition

These comparisons help examine how different employee features are
associated with attrition.

---

### 5. Correlation Analysis

A correlation heatmap was created to identify relationships between
the numerical features in the dataset.

The heatmap provides a visual representation of the strength and
direction of correlations between employee characteristics and
attrition.

---

## Key Questions Analyzed

The analysis investigated the following questions:

1. What is the overall employee attrition rate?

2. How does overtime relate to employee attrition?

3. How does job satisfaction relate to employee attrition?

4. How do years at the company differ between employees who stayed
   and employees who left?

5. How does monthly income differ between employees who stayed and
   employees who left?

6. What relationships can be observed between numerical features
   using correlation analysis?

---

## Key Findings and Conclusion

The Exploratory Data Analysis provided an overview of employee
characteristics and their relationship with attrition.

The analysis examined age, monthly income, job satisfaction, years at
the company, overtime, work-life balance, and job level.

The visualizations helped identify patterns and differences between
employees who stayed and employees who left.

The correlation analysis provided additional information about the
relationships between numerical features.

Overall, this project demonstrates how Exploratory Data Analysis can
be used to understand employee data, identify meaningful patterns,
and generate useful insights.

The findings from this analysis can be used as a foundation for
further employee attrition prediction and machine learning projects.

---

## Tools and Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## Project Structure

```text
Thiranex_Task3_EDA/
│
├── EDA_Employee_Attrition.ipynb
├── employee_attrition_data.csv
├── README.md
│
└── visualizations/
    ├── age_distribution.png
    ├── salary_distribution.png
    ├── job_satisfaction.png
    ├── attrition_distribution.png
    ├── attrition_by_overtime.png
    ├── attrition_by_job_satisfaction.png
    ├── years_at_company_vs_attrition.png
    ├── income_vs_attrition.png
    ├── correlation_heatmap.png
    └── attrition_rate_by_overtime.png