
# HR Data Analysis Report (mySQL-PowerBI)
In this project, we clean and process HR data to answer the following questions using mySQL and PowerBI. 

![App Screenshot](https://i.postimg.cc/50Hkck9k/Screenshot-2023-07-06-224805.png)
![App Screenshot](https://i.postimg.cc/BnK66JYq/Screenshot-2023-07-06-233632.png)

# Data Used
**Data** - HR Data with over 22000 rows from the year 2000 to 2020.

**Data Cleaning & Analysis** - MySQL Workbench

**Data Visualization** - PowerBI

# Questions And Answers

#### 1. What is the gender breakdown of employees in the company?
- There are more male employees
#### 2. What is the race/ethnicity breakdown of employees in the company?
- White race is the most dominant while Native Hawaiian and American Indian are the least dominant.
#### 3. What is the age distribution of employees in the company?
- The youngest employee is 20 years old and the oldest is 57 years old. 5 age groups were created (18-24, 25-34, 35-44, 45-54, 55-64). A large number of employees were between 25-34 followed by 35-44 while the smallest group was 55-64.
#### 4. How many employees work at headquarters versus remote locations?
- A large number of employees work at the headquarters versus remotely.
#### 5. What is the average length of employment for employees who have been terminated?
- The average length of employment for terminated employees is around 7 years.
#### 6. How does the gender distribution vary across departments?
- The gender distribution across departments is fairly balanced but there are generally more male than female employees.

#### 7. Which department has the highest turnover rate?
- The Marketing department has the highest turnover rate followed by Training. The least turn over rate are in the Research and development, Support and Legal departments.
#### 8. What is the distribution of employees across locations by state?
- A large number of employees come from the state of Ohio.
#### 9. How has the company's employee count changed over time based on hire and term dates?
- The net change in employees has increased over the years.
#### 10. What is the tenure distribution for each department?
- The average tenure for each department is about 8 years with Legal and Auditing having the highest and Services, Sales and Marketing having the lowest.

# Limitations
- Some records had negative ages and these were excluded during querying(967 records). Ages used were 18 years and above.
- Some termdates were far into the future and were not included in the analysis(1599 records). The only term dates used were those less than or equal to the current date.
