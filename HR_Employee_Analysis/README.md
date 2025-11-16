# HR Data Cleaning & Analysis – SQL Project

## Project Overview
This project involved **data cleaning, preprocessing, and analysis** of HR datasets using **MySQL** for SQL queries and **Power BI** for visualization. The goal was to understand employee demographics, tenure, turnover, and departmental performance.

## Key Contributions
- **Data Cleaning & Preprocessing:** Corrected column names, standardized date formats, handled missing values, and calculated new fields (e.g., employee age).  
- **Data Analysis:** Explored employee demographics, tenure, job distribution, gender and race breakdowns, department performance, turnover rates, and hiring trends using MySQL queries.  
- **Insights Generation:** Visualized results in Power BI to extract actionable insights.

## HR Database Cleaning Steps
- Fixed column naming inconsistencies  
- Standardized date formats for `birthdate`, `hire_date`, and `termdate`  
- Calculated employee ages  
- Handled missing or null values to ensure data integrity

## SQL Analyses Performed
- Gender breakdown of employees  
- Race/Ethnicity distribution  
- Age group distribution  
- Gender across age groups  
- HQ vs Remote employee counts  
- Average length of employment (terminated employees)  
- Gender distribution by department & job title  
- Job title distribution  
- Department with highest turnover  
- Employee distribution across states  
- Employee count change over time  
- Tenure distribution per department  

*(SQL queries used are included in `hr_analysis_queries.sql`.)*

## Insights from Data Analysis & Power BI Visuals
- **Gender:** More male employees than female employees.  
- **Race/Ethnicity:** White employees are most dominant; Native Hawaiian and American Indian employees are least represented.  
- **Age Distribution:** Employees range from 20 to 57 years old. Most are 25-34, followed by 35-44; smallest group is 55-64.  
- **Location:** Most employees work at headquarters versus remote locations.  
- **Average Length of Employment:** Terminated employees averaged around 7 years.  
- **Gender Distribution Across Departments:** Fairly balanced, with slightly more males.  
- **Department Turnover:** Marketing has the highest turnover rate, followed by Training; Research & Development, Support, and Legal have the lowest.  
- **Employee Distribution by State:** Ohio has the most employees.  
- **Employee Count Over Time:** Net employee count has increased, showing company growth.  
- **Tenure Distribution by Department:** Average tenure ~8 years; Legal & Auditing highest, Services, Sales & Marketing lowest.

## Project Files
- [HR Dataset (CSV)](Human%20Resources.csv)  
- [SQL Queries](hr_analysis_queries.sql)  
- [Power BI Visuals](HR_Employee_Report.pbix)  
- [Project Report (PDF)](HR_Employee_Report.pdf)  

## Tools Used
- **MySQL:** Ran queries for data cleaning, preprocessing, and analysis.  
- **Power BI:** Visualized SQL results and generated actionable insights.  
- **Python / Excel:** Optional for additional analysis or preprocessing.

## How to Use
1. Open `Human Resources.csv` to view the raw dataset.  
2. Run SQL queries in `hr_analysis_queries.sql` on your MySQL database.  
3. Open `HR_Employee_Report.pbix` in Power BI to explore visualizations.  
4. Read `HR_Employee_Report.pdf` for a summary of findings and conclusions.
