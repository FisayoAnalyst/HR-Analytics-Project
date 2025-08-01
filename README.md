# HR Analytics Project

### Table of Contents
[Overview](#overview)

[Objective](#objective)

[Dataset Information](#dataset-information)

[Tools Used](#tools-used)

[Data Cleaning & Transformation](#data-cleaning--transformation)

[Dashboard Overview](#dashboard-overview)

[Key Findings](#key-findings)

[Recommendations](#recommendations)

[Conclusion](#conclusion)

[Report Access](#report-access)

[Dashboard Access](#dashboard-access)

### Overview

This HR Analytics project explores key workforce trends using Excel-based data analysis. The focus is on understanding attrition drivers, job satisfaction, and managerial impact on employee engagement. The insights are designed to guide human resource teams in making informed, data-driven decisions for improving retention and workplace well-being.

### Objective

This analysis was conducted to:

- Identify key factors driving employee turnover

- Analyze attrition by age, education, tenure, and department

- Evaluate the role of job satisfaction and work-life balance in retention

- Understand the influence of managers and leadership on employee morale

- Provide actionable HR strategies to reduce attrition

### Dataset Information

**Source**: [Kaggle.com](https://www.kaggle.com/)


**Key Attributes**:

- `EmployeeID`, `Gender`, `Age`, `Department`, `DistanceFromHome`,

- `Salary`, `Attrition`, `JobSatisfaction`, `ManagerRating`, `PerformanceRating`, `WorkLifeBalance`

The dataset includes 1,470 employees with 237 attritions (16.12% attrition rate).

### Tools Used

**Excel** (Power Pivot, Power Query, Pivot Tables, Charts)

**DAX** for calculated columns and KPIs

### Data Cleaning & Transformation

- Linked tables via `EmployeeID` using **Power Pivot**

- Removed duplicates, handled missing values in **Power Query**

- Created custom categories (e.g., commute distance buckets)

- Built calculated columns using DAX (e.g., age group classification)

- Generated insights via pivot tables and Excel visualizations

### Dashboard Overview

The HR Analytics Dashboard summarizes:

- Attrition trends by gender, age, distance, and department

- Job satisfaction by age, gender, and travel frequency

- Manager ratings across departments

- Work-life balance by travel role

- Key summary metrics such as average salary, tenure, and satisfaction scores
  
<img width="1850" height="778" alt="HR Overview DB" src="https://github.com/user-attachments/assets/817cde26-e93d-4295-a9b1-26122a00b534" />

### Key Findings

- Highest attrition occurs among employees aged 25–35 and in the Technology department

- Employees with long commutes and frequent travel report lower satisfaction and higher attrition

- HR department scored highest in manager ratings

- Attrition is lower among employees with doctoral degrees

- Average job satisfaction: 3.43 | Work-life balance: 3.41

### Recommendations

1. Develop mentorship and career advancement for employees aged 25–35

2. Introduce hybrid work options to reduce long commute-related attrition

3. Revisit compensation in the Technology department

4. Adjust travel policies to enhance work-life balance

5. Strengthen inclusivity and employee engagement programs

### Conclusion

This HR analytics project provided key insights into workforce trends such as attrition patterns, departmental distribution, age segmentation, and job satisfaction levels. Using Excel, I was able to clean the data, create visualizations, and uncover areas that can inform better HR decisions.

The analysis highlights the importance of data in addressing employee retention, engagement, and compensation planning. This project demonstrates how simple tools like Excel can support strategic workforce management through clear, actionable insights.

### Report Access

You can read the full technical report in PDF format:
➡️ Download HR Analytics Report (PDF) (https://github.com/FisayoAnalyst/HR-Analytics-Project/blob/main/HR_Analytics_Report.pdf)

### Dashboard Access

To explore the interactive visuals, open the Excel dashboard file:

➡️ Download the HR Dashboard File (https://github.com/FisayoAnalyst/HR-Analytics-Project/blob/main/Human%20Resouces.xlsx)

