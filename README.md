# HR Analytics: Employee Attrition & Retention Dashboard
![Dashboard 1](https://github.com/Chukwuma-Onyekpandu/Beyond-the-Resignation-Letter-A-Data-Driven-Deep-Dive-into-Employee-Attrition/blob/main/Screenshot%202025-06-24%20223315.png)
![Dashboard 2](https://github.com/Chukwuma-Onyekpandu/Beyond-the-Resignation-Letter-A-Data-Driven-Deep-Dive-into-Employee-Attrition/blob/main/Screenshot%202025-06-24%20223407.png)
![Dashboard](https://github.com/Chukwuma-Onyekpandu/Beyond-the-Resignation-Letter-A-Data-Driven-Deep-Dive-into-Employee-Attrition/blob/main/Screenshot%202025-06-24%20223449.png)


### Project by Onyekpandu Chukwuma

---

### Project Overview

This project involves a comprehensive analysis of an HR dataset to understand the key factors driving employee attrition. Using Power BI, a detailed, interactive dashboard was developed to explore demographic, performance, and satisfaction data, ultimately providing actionable recommendations to improve employee retention.

### Problem Statement & Objectives

The primary objective of this analysis was to identify the root causes of employee turnover. The goal was to answer critical business questions, such as:
- Which departments and job roles have the highest attrition rates?
- What demographic profiles are most at risk of leaving?
- How do factors like overtime, salary hikes, and job satisfaction correlate with attrition?
- What data-driven strategies can be implemented to reduce turnover and retain valuable talent?

### Dataset

The analysis was performed on a synthesized HR dataset containing 1,470 employee records. Each record includes 35 features related to employee demographics, compensation, job role, performance ratings, and satisfaction scores, with a clear `Attrition` flag for each employee.

### Tools Used

- **Microsoft Power BI:** Used for data modeling, creating DAX measures, and building all interactive dashboard visuals.
- **Power Query:** Used for all data cleaning, transformation, and preparation steps.
- **DAX (Data Analysis Expressions):** Used to create key performance indicators (KPIs) such as `Attrition Rate %`.

---

### Data Cleaning & Preparation

Before analysis, the data was thoroughly prepared and enhanced in Power Query to ensure accuracy and usability:
- **Feature Engineering:** A calculated `Age Group` column was created to segment employees for better analysis. Date component columns (Year, Month, Day of Week) were also created.
- **Data Transformation:** Key DAX measures like `[Total Employees]`, `[Attrition Count]`, and `[Attrition Rate %]` were created to serve as the foundation for the analysis.
- **Data Integrity:** The dataset was pre-cleaned and contained no empty rows or errors in the critical columns, providing a solid base for analysis.

### Data Analysis & Key Findings

[cite_start]The analysis of 1,470 employee records revealed an overall **Attrition Rate of 16.12%**, with 237 employees having left the company. The drivers of this attrition are not uniform across the company.

- **Departmental Insights:**
  - [cite_start]The Research & Development department had the highest absolute number of leavers with **133** employees.
  - [cite_start]However, the **Sales** department had the highest attrition *rate* at **20.63%**, indicating a more severe systemic issue with retention.
  - [cite_start]The Human Resources department had the second-highest rate at **19.05%**.

- **Job Role & Level Insights:**
  - Attrition is heavily concentrated in specific roles. [cite_start]The **`Sales Representative`** role has an extremely high attrition rate of **39.76%**.
  - [cite_start]Conversely, leadership roles like **`Manager` (4.90%)** and **`Research Director` (2.50%)** show very strong retention.
  - Attrition is most severe at junior levels. [cite_start]The highest number of leavers (**40**) are at **`JobLevel` 1** with only 1 year of total working experience.
  - [cite_start]Within the Sales department, employees at **`JobLevel` 1** have the highest attrition rate of **42.11%**.
  - [cite_start]`Marketing` at **`JobLevel` 1** also shows a very high attrition rate of **57.14%**.

- **Demographic Insights:**
  - Younger employees are significantly more likely to leave. [cite_start]The **18-25 age group** shows the highest attrition rate by a large margin at **35.77%**.

- **Work Style & Compensation Insights:**
  - [cite_start]Employees who work **overtime** are more likely to leave, with **127** leavers from this group compared to **110** from the non-overtime group.
  - Annual salary hikes do not appear to be a primary driver. [cite_start]The total `PercentSalaryHike` for employees who left was 3578, while for those who stayed it was 18780, resulting in nearly identical averages.
  - Career stagnation, however, is a clear factor. [cite_start]Attrition rates show significant spikes for employees who have gone **7 years (21.05%)** or **15 years (23.08%)** without a promotion.

- **Employee Satisfaction Insights:**
  - Low satisfaction scores are strong predictors of attrition. [cite_start]Among employees who left, a significant portion reported low **`WorkLifeBalance`** (scores 1 and 2).
  - [cite_start]Similarly, employees who left also reported a higher proportion of low **`JobSatisfaction`** scores compared to those who stayed.

### Visualizations

The Power BI dashboard includes a variety of visualizations to tell the attrition story, including:
- **KPI Cards:** Displaying the overall `Attrition Rate %`, total employee count, and other key metrics.
- **Bar Charts:** Comparing attrition rates across dimensions like `Department`, `Job Role`, and `Age Group`.
- **100% Stacked Bar Charts:** To visually compare the distribution of satisfaction scores for employees who left versus those who stayed.
- **Line Chart:** To show the relationship between `YearsSinceLastPromotion` and the attrition rate.

### Actionable Recommendations

Based on the analysis, several key strategies were recommended to leadership:
1.  [cite_start]**Develop a Targeted "Early Career Engagement Program"** focused on the high-risk 18-25 age group and junior-level roles like Sales Representative, who have attrition rates of 35.77% and 39.76% respectively.
2.  [cite_start]**Implement Department-Specific Retention Plans**, addressing the systemic issues causing the high *rate* in Sales (20.63%)  while providing scalable support for the large R&D department.
3.  [cite_start]**Overhaul the Career Progression Framework** to combat the career stagnation that affects long-tenured employees, especially those who have gone 7 or more years without a promotion.
4.  [cite_start]**Utilize Employee Satisfaction Surveys** as a proactive early warning system to identify at-risk employees before they decide to leave.

---
