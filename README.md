  # BI_SQL_Project-HrEmployeeDistributionReport

![HR-Employee-Distribution-Report](https://github.com/zarnikhinkyi/bi_sql_project-HrEmployeeDistributionReport/assets/77061456/18f61bb1-c460-4077-8d38-5b7c67fa8c61)
![HR-Employee-Distribution-Report-2](https://github.com/zarnikhinkyi/bi_sql_project-HrEmployeeDistributionReport/assets/77061456/86b6302f-b928-446e-9924-c6c018e3fa6b)
![HR-Employee-Distribution-Report-3](https://github.com/zarnikhinkyi/bi_sql_project-HrEmployeeDistributionReport/assets/77061456/fee9f1f4-f79a-4497-a149-fe2325e6f051)
![HR-Employee-Distribution-Report-4](https://github.com/zarnikhinkyi/Power-BI-SQL-Project_HrEmployeeDistributionReport/assets/77061456/75d59b8c-0b1c-4f03-ac3f-76edb2019365)


# Questions for Report
- **What is the gender breakdown of employees in the company?**
- **What is the race/ethnicity breakdown of employees in the company?**
- **What is the age distribution of employees in the company?**
- **How many employees work at headquarters versus remote locations?**
- **What is the average length of employment for employees who have been terminated?**
- **How does the gender distribution vary across departments and job titles?**
- **What is the distribution of job titles across the company?**
- **Which department has the highest turnover rate?**
- **What is the distribution of employees across locations by city and state?**
- **How has the company's employee count changed over time based on hire and term dates?**
- **What is the tenure distribution for each department?**


# Summary of Findings
- **There are more male employees**
- **White race is the most dominant while Native Hawaiian and American Indian are the least dominant.**
- **The youngest employee is 20 years old and the oldest is 57 years old**
- **5 age groups were created as 18-24, 25-34, 35-44, 45-54, 55-64. A large number of employees were between 25-34 followed by 35-44 while the smallest group was 55-64.**
- **75% of employees are working at the headquarters versus 25% are at remotely.**
- **The average length of employment for terminated employees is around 8 years.**
- **The gender distribution across departments is fairly balanced but there are generally more male than female employees.**
- **Auditing, Training,and Legal department has the highest turnover rate. Marketing and Business Development has least turnover rate.**
- **A large number of employees are from Ohio state.**
- **The net change in employees has increased over the years.**
- **The average tenure for each department is about 8 years with Accounting, Auditing, and Engineering having the highest and Legal, and Product Management having the lowest.**

# Limitation in the analysis
- **Some records had negative ages and these were excluded during querying. Ages used were 18 years and above (age>=18).**
- **Some termdates were far into the future and were not included in the analysis. The only term dates used were those less than or equal to the current date.**

# Data Used
  - **HR Data with over 2200 rows**
  - **MySQL Workbench used for Data Cleaning and Analysis**
  - **Power BI used for Data Visualization**
