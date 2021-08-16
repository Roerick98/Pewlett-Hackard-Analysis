# Pewlett-Hackard-Analysis

## Overview
The purpose of our project is to determine the number of retiring employees by title and identify which employees are eligible to to participate in the mentorship program. The list of retiring employees will show the titles of all employees born between January, 1 1952 and December, 31 1955. First we created a query that retrieved the emp_no, first_name and last_name columns from the employees table and retrieved the title,from_date and to_date columns of the titles table in our pewlett-hackard query. We joined both of these tables on the primary key,filtered the data by birth_date and dumped the information into a new table. For the next two parts of deliverable 1 we created a unique_titles table to find the first occurance of the emp_no in our new table by using the DISTINCT ON function and for the last part of the deliverable we did ORDER BY COUNT to show us the total number of each title from our unique_titles table that we created. For the second deliverable, we wrote a query that retrieved columns from our employees and dept_emp table, filtered data on current employees born in 1965, then ordered the table by emp_no.

## Results
- According to the retiring_titles dataset, a large majority of employees that are retiring possess senior titles. ![EmployeeData](https://user-images.githubusercontent.com/35403433/129517647-73875da3-3679-4cc0-9afe-1ee3b412e8d9.png)
- The unique_titles dataset was designed to show the most recent title of retiring employees.
- The retirement_titles dataset shows every employee eligible for retirement, their title, and when they began their current position at the company.
- Finally the mentorship_eligibility dataset sorts through the list of retiring employees and returns those that were born in the year 1965 and were thus eligible for a mentorship program.![Mentorship](https://user-images.githubusercontent.com/35403433/129518127-72888993-4e43-4d3f-b185-b68ed51969c6.png)

## Conclusion
Seeing as there are many senior positions that will need to be filled, there will most likely be many opportunities for promotion through the mentorship program. There may not be enough candidates to fill these positions, so the company will probably need to hire outside candidates.
