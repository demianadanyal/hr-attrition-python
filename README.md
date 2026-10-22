# HR Employee Attrition Analysis (Python)

## Overview
Exploratory data analysis of an HR dataset (1,470 employees) to understand why employees leave the company. Built in a Python analytical notebook as part of the Advanced Data Analysis course at NTI.

## Business Questions
1. What is the overall attrition rate?
2. Which department and job role have the highest attrition rate?
3. How does overtime relate to attrition?
4. Does monthly income differ between employees who stayed and those who left?
5. Is age related to attrition?
6. Which numeric variables correlate most strongly with attrition?

## Tools
Python, Pandas, Seaborn, Matplotlib, Jupyter Notebook

## Project Files
- [Analysis notebook](notebook/hr_attrition_analysis.ipynb)
- [Full report (PDF)](report/assignment_8.pdf)

## Key Findings
1. **Overall attrition:** 16.1% of employees left (237 out of 1,470), while 83.9% are current employees.
2. **Department and role:** Sales has the highest attrition rate among departments (20.6%), and Sales Representative is the highest-attrition role (39.8%).
3. **Overtime:** Employees who work overtime leave at a rate of 30.5%, versus only 10.4% for those who don't.
4. **Income:** Employees who left earned an average monthly income of $4,787, versus $6,833 for those who stayed.
5. **Age:** Employees who left are younger on average (33.6 years) than those who stayed (37.6 years).
6. **Correlations:** All correlations with attrition are weak (below 0.2). The strongest are total working years, job level, and monthly income, all negative.

## Recommendations
- Review overtime policies, since overtime is linked with a three-fold higher attrition rate.
- Focus retention efforts on the Sales department, especially Sales Representatives.
- Check salary competitiveness for lower-paid and junior roles.
- Target early-career employees with career development and mentoring.
