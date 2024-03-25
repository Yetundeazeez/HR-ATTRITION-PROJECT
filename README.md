# HR ATTRITION PROJECT



---
## **Project Outline**
- [Project Overview](#Project-Overview)
- [Dataset](#Dataset)
- [Tools Used for Analysis](#Tools-Used-for-Analysis)
- [Data Cleaning and Transformation](#Data-Cleaning-and-Transformation)
- [Query 3](#Query-3)
- [Query 6](#Query-6)
- [Tools Used](#Tools-Used)
- [Results and Findings](#Results-and-Findings)
- [Recommendation](#Recommendation)
---

## Project Overview
The purpose of this project is to perform data analysis on the HR ATTRITION dataset based on the indicators that mostly affect the employment status of employees in a company.

This project report focuses on four important insights which are
1. Demographic insights reflects the summary of the employee statistics which includes the age group, 
gender, marital status, etc.

2. Turnover Analysis I provides insights on employee attrition which includes departure by department, job role, working years, business travel, etc

3. Turnover Analysis II provides insights on monthly income, overtime, job level, etc.

4. Employee Wellness provides insights on job involvement, work life balance, performance rating, etc.


---
## Dataset
The dataset used can be downloaded 
[here](https://drive.google.com/file/d/1sBnniRB8LApHtMCEED0_rf3mLA0Abrtf/view?usp=drivesdk)

---

## Tools Used for Analysis 
The dataset used can be downloaded 

---

## Data Cleaning and Transformation
The following data cleaning and transformation processes perform on the dataset:

I loaded the HR ATTRITION datasets into Power BI for cleaning and transformation. 

After which I made the first row of the dataset as the header. 

I also checked for duplicate and missing values. 
The data types for some the variable names starting from the Age, distance from home, employee count, etc were also changed to whole number.

I added a conditional column by taking the dataset to the power query editor to calculate the attrition count and then changed the data type to whole number.

I used the DAX functions to calculate the Current Employee and Attrition rate.

I used data groups on the following variables to aggregate certain values together for meaningful insights:
1. Age group - Ages 18, 19, 20 to 30 are grouped as '18-30', ages 31, 32 to 35 are grouped as '31-35' and ages 46 to 60 are grouped as '46-60'.
2. Distance from Home - 1-10 is considered as 'Near', 10-20 is considered as 'Far' and 20-30 is considered as 'Very far'.
3. Work Life Balance - Value 1 is considered as 'Bad', value 2 is considered as 'Average', value 3 as 
'Good' and value 4 is considered as 'Excellent'.
4. 



---

## Results and Findings

---

## Recommendation
