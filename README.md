# Mental Health & Workplace Analysis

## Overview
This repository contains an analysis of employee mental health and workplace data. The goal is to uncover patterns in stress, work-life balance, productivity, and overall well-being, providing actionable insights for organizations.

The analysis focuses on identifying **high-risk employees**, understanding **workload distribution**, and visualizing correlations between mental health, sleep quality, and productivity.

---

## Dataset Columns
Key columns included in the dataset:

- Employee ID  
- Age  
- Gender  
- Job Role  
- Industry  
- Years of Experience  
- Work Location  
- Hours Worked per Week  
- Number of Virtual Meetings  
- Work-Life Balance Rating  
- Stress Level  
- Mental Health Condition  
- Access to Mental Health Resources  
- Productivity Change  
- Social Isolation Rating  
- Satisfaction with Remote Work  
- Physical Activity  
- Sleep Quality  
- Region  

---

## High-Risk Employee Classification
Employees were classified as **high-risk** if **any** of the following conditions were met:  

1. Mental health condition is Burnout, Anxiety, or Depression **AND** poor sleep quality **AND** no access to mental health resources  
2. Working **overtime (>50 hours/week)**  

Additionally, employees **over 60 working overtime** are flagged as **High Risk – Retirement Suggested**.

**Power BI Implementation:**  
- `Risk Status` calculated column (DAX) to categorize employees  
- `Workload Category` column (Overtime, Regular, Undertime) for analysis  

---

## Workload Assessment
- **Overtime:** >50 hours/week  
- **Regular:** 30–50 hours/week  
- **Undertime:** <30 hours/week  

---

## Key Insights
- High-risk employees identified based on mental health, sleep, access to resources, and working hours  
- Overtime and undertime patterns highlight employees at risk of burnout or disengagement  
- Employees over 60 working overtime are flagged for retirement consideration  
- Interactive dashboards show actionable insights for HR strategy and workplace interventions

---

## Tools & Techniques
- **Power BI:** Interactive dashboards, calculated columns, DAX measures  
- **Data Cleaning & Transform**
