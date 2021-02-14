# Written Analysis of the Pewlett- Hackard Employee retirement Data Analysis

## Overview of Analysis
This project is about analysis of employee data of Pewlett-Hackard for their aging employees  born between 1952-1955 who will soon retire from the company and to help Pewlett management understand if they have enough mentors available to train other employees to take up these open positions. SQL queries were created to retreive data using various tables for the databases and with use of Joins, Distinct, Count, group and Order, good data was retrieved.

### Purpose
The purpose of this data analysis is to identify the retiring employees by title/roles and availability for mentorship progream which will help Pewlett-Hackard to plan to fill the role gaps due to so many employees retiring across the organization. 

#### Deliverable: This analysis and SQL queries consists of a technical analysis deliverables and a written report for Data Analysis:

- Deliverable 1: The Number of Retiring Employees by Title
Queries: https://github.com/archinarula/Pewlett-Hackard-Analysis/blob/main/Queries/Employee_Database_Challenge.sql

3 Data exports csv files for reference: 
Retirement_titles.csv- https://github.com/archinarula/Pewlett-Hackard-Analysis/blob/main/Data/retirement_titles.csv
Unique_titles.csv- https://github.com/archinarula/Pewlett-Hackard-Analysis/blob/main/Data/unique_titles.csv
Retiring_titles.csv- https://github.com/archinarula/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles.csv

- Deliverable 2: The Employees Eligible for the Mentorship Program
Queries: https://github.com/archinarula/Pewlett-Hackard-Analysis/blob/main/Queries/Employee_Database_Challenge.sql

1 Data exports csv files for reference:
mentorship_eligibility.csv- https://github.com/archinarula/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibility.csv

- Deliverable 3: A written report on the employee database analysis  
https://github.com/archinarula/Pewlett-Hackard-Analysis/blob/main/README_Written_Analysis_Module7%20Challenge.md

## Results

### There is a bulleted list with four major points from the two analysis deliverables.

1. The retirement_titles.csv shows all the employees eligible for retirement with their tenure served in this company. The unique_titles.csv shows all the employees of retirement age currently with the company and their most recent titles. Reviewing these two outputs shows that this company is going to have 90398 employees retiring soon which is a huge number to fill the openings for and to sustain operations in near future for this company

2. From the retiring_titles.csv we can see that 99.997% retiring employees belong to technical roles with only 2 managers at impact. 
[! Retiring titles.png] 
(https://github.com/archinarula/Pewlett-Hackard-Analysis/blob/main/Retiring%20titles.png)

3. From the retiring_titles.csv we can also see that maximum impact in the Senior employees of this company (Senior Engineer and Senior Staff) which means 64% of all retiring employees have senior titles

4. Finally, the mentorship_eligibility.csv shows that company has very few mentors (1549) available as compared to total retiring employees and the roles for which company needs to training people to fill this gap. There are only 45% mentor eligibles for the Senior title mentoring (711/1549) and they have no mentors for Manager training.
[! mentors.png] 
(https://github.com/archinarula/Pewlett-Hackard-Analysis/blob/main/mentors.png)

## Summary: 

### How many roles will need to be filled as the "silver tsunami" begins to make an impact?
There are 90398 across 7 job roles with retiring employees that will be impact in near future and would need to be filled up

### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
No, this company does not have enough qualified, retirement- ready employees in the departments to mentor the next generation of employees. There are only  1.7% of mentors availability i.e. only 1549 mentors available across the departments to cover trainings for 90398 job openeings that will be needed in coming years which is a huge gap of intellectual loss for Pewlett hackard.

Company can look into the employees tables to see employees not retirement eligibility (above birth date 1955) then look into the Senior Titles and also get some of those to start mentoring to speed up the training process.
[non_retiring.png]
(https://github.com/archinarula/Pewlett-Hackard-Analysis/blob/main/non_retiring.png)






