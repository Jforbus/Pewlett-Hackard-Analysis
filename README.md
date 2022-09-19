# Pewlett-Hackard-Analysis

## Project Overview

Pewlett Hackard has requested the following analysis be conducted to aid in the "future-proofing" of the company. Preliminary analysis have observed that a significant portion of Pewlett - Hackard's is approaching retirement eligibility. Senior leadership has requested the following in order to better understand and prepare for the coming wave of retirements.

    1. The total number of retiring employees for each job title. 

    2. A table containing all employees eligible for a proposed mentorship program. 

### Resources

- Data Source: employees.csv, departments.csv, dept_emp.csv, dept_manager.csv, salaries.csv, titles.csv
- Software: PostgreSQL 11, pgAdmin 4

## Results
When we look at the results of this analysis we see 4 major points revealed in the data.

    - 70% (50,842) of the retirement elegible employees are in Senior positions.
    `insert senior_positions.png`
    - 7 different job titles are due to be affected by retirements. 
    - A relatively small number of employees are retiring from low level positions.
    - 1,549 employees are eligible for the mentorship program.
### Summary
When this wave begins a total of 72,458 employees are due to reach retirement eligibility very rapidly. The majority of the positions that will need to be filled will be Senior positions, namely Senior Staff and Senior Engineer. 

Current employees capable of mentoring the next generation are greatly exceeded by the enormous number of positions that will need to be filled. Employees eligible for the mentorship program account for only 2% of the total of retirement eligible employees.

The database should be queried to determine the total number of employees at Pewlett-Hackard. This paired with the above analysis will allow leadership to better understand the challenge it is up against.

An additional table that details the number of employees by job title that are not approaching retirement eligibility could be created. This would give Pewlett-Hackard greater perspective on the portion of each job title that will be retained during the coming retirements, potentially revealing other helpful details.

Also, another table that groups the employees eligible for the mentorship program by job title would be helpful. This would allow leadership to see which job titles will be able to take advantage of the mentorship program, and which lack eligible employees to participate.  