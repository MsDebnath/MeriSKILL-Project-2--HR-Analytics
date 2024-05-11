# MeriSKILL-Project-2--HR-Analytics
Delving into the world of human resources, with a keen eye on data analysis to optimize talent management and organizational performance.

## Introduction
This project dives into the human resources realm, leveraging data analysis to unlock insights that optimize talent management and, ultimately, propel organizational performance.  The focus here is on employee attrition, and the tools provided aim to shed light on factors influencing workforce departures. By harnessing the power of data visualization, this project empowers HR professionals to make informed decisions that cultivate a thriving and engaged workforce.

## Purpose
This HR attrition dashboard serves a multi-faceted purpose, providing a comprehensive view of employee turnover across the organization. It is designed with five key pages:

* Overview: This introductory page offers a high-level summary of all four subsequent dashboards, giving a quick grasp of overall attrition trends.
* Demographic Insights: This section delves deeper, analyzing employee demographics such as age, tenure, department, or any other relevant factors to identify potential correlations with turnover.
* Turnover Analysis 1: This page focuses on a specific aspect of employee turnover, allowing for a granular examination of contributing factors.
* Turnover Analysis 2: Building upon the first turnover analysis, this section explores another dimension of employee departures, providing a well-rounded understanding.
* Employee Wellness: Recognizing the connection between employee wellbeing and retention, this final page explores wellness metrics to identify potential areas for improvement in fostering a positive work environment.

Through this comprehensive approach, the HR attrition dashboard empowers data-driven decision making, enabling proactive strategies to improve employee retention and optimize talent management.

## The Dataset
The datase has 35 columns.
  * Age
  * Gender
  * Marital Status
  * Education
  * Education Field
  * Department
  * Job Role
  * Job Level
  * Years At Company
  * Years In Current Role
  * Num Companies Worked
  * Adult
  * Monthly Income
  * Hourly Rate
  * Percent Salary Hike
  * Daily Rate
  * Monthly Rate
  * Standard Hours
  * Over Time
  * Stock Option Level
  * Business Travel
  * Distance From Home
  * Environment Satisfaction
  * Job Satisfaction
  * Work-Life Balance
  * Relationship Satisfaction
  * Performance Rating
  * Job Involvement
  * Training Times Last Year
  * Years Since Last Promotion
  * Years With Curr Manager
  * Employee Number
  * Employee Count
  * Total Working Years

## Visualization

![HR Analytics](https://github.com/MsDebnath/MeriSKILL-Project-2--HR-Analytics/assets/134738648/f59736a6-e287-4f38-933b-bd49d7ff9b29)
![HR Analytics D](https://github.com/MsDebnath/MeriSKILL-Project-2--HR-Analytics/assets/134738648/8d0d5128-2dcb-4c28-b57d-28f4595b8423)
![HR Analytics TA1](https://github.com/MsDebnath/MeriSKILL-Project-2--HR-Analytics/assets/134738648/ea9a2a60-eaa7-4796-8a46-be9252ab2a06)
![HR Analytics TA2](https://github.com/MsDebnath/MeriSKILL-Project-2--HR-Analytics/assets/134738648/3916acdc-5c4d-44c0-bc6a-742837f295ab)
![HR Analytics EW](https://github.com/MsDebnath/MeriSKILL-Project-2--HR-Analytics/assets/134738648/90f28495-98df-4b0c-8523-237856f7ad89)

## Insights

### _Demographics_
**Demographics Insights:**

- **Total Employees**: The company has a workforce of 1470 employees.
- **Attrition Rate**: A notable portion of the workforce, 16% (237 employees), left the company.
- **Retention Rate**: Despite the attrition, 84% (1233 employees) of the total workforce remained in the company.
- **Gender Disparity**: Male employee attrition is significantly higher at 63% compared to female attrition at 37%. This suggests potential gender-specific issues affecting retention.
  
**Education Field Insights:**

- **Life Science**: The highest attrition rate is seen among employees with a background in Life Science, with 89 out of 606 employees leaving. This field has the highest total attrition.
- **Medical and Marketing Fields**: While attrition rates are relatively lower in these fields, a considerable number of employees still left (63 and 35 respectively).
- **Technical Degree and Other Fields**: Attrition rates in these fields are moderate compared to others, indicating a relatively stable workforce.

**Age Group Insights:**

- **Youth Attrition**: The highest attrition occurs in the age group of 18 to 30, suggesting potential issues related to early career development, job satisfaction, or work-life balance.
- **Middle-Aged Employees**: Attrition rates decrease with age, indicating potentially higher job stability or satisfaction among older employees.

**Work-life Balance Insights:**

- **Work-life Balance Impact**: Employees with a good work-life balance represent the highest proportion of those who left the company. This suggests that factors beyond work-life balance alone may be contributing to attrition.
- **Excellent Work-life Balance**: Surprisingly, employees with an excellent work-life balance also contributed to attrition, albeit in smaller numbers.

**Distance from Home Insights:**

- **Proximity to Home**: Attrition rates are highest among employees living near the workplace, which may suggest that factors other than commuting distance are influencing their decisions to leave.

**Marital Status Insights:**

- **Single Employees**: Single employees form the largest group in terms of attrition. There is a gender disparity within this group, with more male single employees leaving compared to females.
- **Married and Divorced Employees**: Attrition rates among married and divorced employees are lower compared to single employees, with married males showing higher attrition compared to females.

**Overall Implications:**

- The data suggests that attrition is influenced by a combination of factors including education field, age, work-life balance, distance from home, and marital status.
- Understanding these demographics can help tailor retention strategies to address specific needs and challenges faced by different employee groups.
- There's a need for further analysis to identify underlying reasons behind gender disparities in attrition rates and to develop targeted interventions to mitigate them.

### _Turnover Analysis I_
**Average Working Year and Total Job Roles**:
  - The average tenure of employees is relatively long, with an average of 11.28 years.
  - There are 9 different job roles within the company, indicating a diverse workforce.
**Job Role Analysis**:
  - The Laboratory Technician role experienced the highest attrition, followed closely by Sales Executive and Research Scientist positions.
  - This suggests potential issues within these roles or departments that need addressing to improve retention.

**Departmental Attrition**:
  - The Research and Development department had the highest attrition rate at 56%, indicating potential challenges or dissatisfaction within this department.
  - Sales department followed with 39% attrition, which could indicate issues related to sales targets, work culture, or job satisfaction.

**Business Travel Impact**:
  - Employees who rarely traveled for business had the highest attrition rate, suggesting that frequent travel might not be a significant factor in attrition.
  - Interestingly, a notable portion of non-business travelers also left, indicating other factors influencing their decision to leave.

**Tenure in Current Role**:
  - A significant number of employees who left were in their roles for less than 2 years, especially in the Research and Development department.
  - This could indicate challenges with onboarding, job fit, or dissatisfaction with the role or company culture among newer employees.

**Longer Tenure Attrition**:
  - While attrition was higher among employees with shorter tenures, there were still cases of attrition among those with longer tenures, particularly in the Sales department.
  - This suggests that factors contributing to attrition may vary regardless of tenure, warranting further investigation into department-specific issues.

**Overall Insights**:
  - Attrition is not uniform across departments or job roles, indicating specific challenges that need targeted solutions.
  - Understanding the factors contributing to attrition, such as job satisfaction, work environment, and career development opportunities, is crucial for implementing effective retention strategies.
  - Addressing department-specific issues and providing support for employees at all tenure levels can help mitigate attrition and improve overall employee satisfaction and retention.
