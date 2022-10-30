# Pewlett-Hackard-Analysis

## Overview of the Analysis:

* Pewlett Hackard is a large company boasting several thousand employees, and it's been around for a long time. As baby boomers begin to retire at a rapid rate, Pewlett Hackard is looking toward the future in two ways. First, it's offering a retirement package for those who meet certain criteria. Second, it's starting to think about which positions will need to be filled in the near future.
The number of upcoming retirements will leave thousands of job openings. What would happen to a company if they didn't look ahead and prepare for this many vacancies? It probably wouldn't be pretty.
Bobby is an up-and-coming HR analyst whose task is to perform employee research. Specifically, he needs to find answers to the following questions: Who will be retiring in the next few years? And how many positions will Pewlett Hackard need to fill? This analysis will help future-proof Pewlett Hackard by generating a list of all employees eligible for the retirement package. The employee data Bobby needs is only available in the form of six CSV files because Pewlett Hackard has been mainly using Excel and VBA to work with their data.
But now, they have decided to update their methods to use SQL, a definite upgrade considering the amount of data. Your task is to help Bobby build an employee database with SQL by applying your data modeling, engineering, and analysis skills.

## Results:

* #1: After creating the ERD throughout module 7, to simplify data our first result was to create a csv file which showed the amount of employeese retiring and the positions they held. By using SQL, we were able to conduct retrieve specfic field from two csv and combine them with a retirementt age parameter to show who is ready for retirement. 
- Reference: [unique_titles.csv](https://github.com/cobb-j/Pewlett-Hackard-Analysis/files/9895295/unique_titles.csv)

* #2: The next result, we had to use a Distinct ON to only show one employee number due to duplicate entries for some employees because they have switched titles over the years. This result as also weeded out those employeese who have left or were terminated. The table that was created from this showed a count of how many employees were retiring and what there current job title was at the time
- Reference:[retiring_titles.csv](https://github.com/cobb-j/Pewlett-Hackard-Analysis/files/9895294/retiring_titles.csv)

* #3: Next we were able to create a new table in a csv file that showed eligibily for Pewlett Hackard's mentorship program. Again in this instance we used distinct on find just one employee name to avoid duplicates and also filter by birth date to show the retirement age and add in the title they carried as current employees. 
- Reference: [mentorship_eligibilty.csv](https://github.com/cobb-j/Pewlett-Hackard-Analysis/files/9895303/mentorship_eligibilty.csv)

* #4: Final Result shows, the 

## Summary:
* How many roles will need to be filled as the "silver tsunami" begins to make an impact?
  - 
* Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
  -
* Additional Queries: 
 
