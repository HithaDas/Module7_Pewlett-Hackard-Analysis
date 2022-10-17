# Pewlett-Hackard-Analysis

# Overview of the analysis -
The purpose of our project is to determine the number of employees retiring in upcoming years by department and identify how many employees are eligible for mentorship program. 

# Results -
1. Employee list retirement titles -
Our retiring employees by title information shows the titles of all employees born between January, 1 1952 and December, 31 1955. First we created a query that retrieved the emp_no, first_name and last_name columns from the employees table and retrieved the title,from_date and to_date columns of the titles table.
We joined both of these table on the primary key,filtered the data by birth_date and put the information into a new table.
The retirment_titles table gives information about who are eligible for retirement and how long they have worked at each position over the time of their career.
Retirement title table stored into a table and its image shown below:

![retirement_titles](https://user-images.githubusercontent.com/110873947/196081451-1576b159-d1ee-43b0-8844-4157f68d7b2f.png)

2. Employees list with unique titles -
We created a unique titles table to find who switched titles over the time of their employment, and hence duplicate entries were removed of those employees. DISTINCT ON method is used for retrieving unique titles.
The unique titles table created shows the most recent title for employee:

![unique_titles](https://user-images.githubusercontent.com/110873947/196081726-fdd318af-88ce-4c49-972d-ec17a4a0f9f8.png)

3. Count of retiring titles -
ORDER BY COUNT is used to find the total number of each title from our unique_titles table. 
Image of retiring title shown below:

![retiring_titles](https://user-images.githubusercontent.com/110873947/196081959-e5f7b1d5-a9a4-463a-9275-172cf21d5350.png)

4. Employee list for mentorship eligibility -
The final part of our challenge is to write a query to find employees who are eligible for mentorship program.
The below image shows list of employees who are eligible for mentorship:

![mentorship_eligibilty](https://user-images.githubusercontent.com/110873947/196082239-946c2cf0-e472-4750-9697-6afc4a9d0967.png)

# Summary -
The analysis helps Bobby and his manager at Pewlett Hackard to prepare for teh "Silver Tsunami" due to the high number of employees retiring in next couple of years in all departments.

72,458 employees will be retiring soon.

Pewlett Hackard can though use mentorship programs to recruit existing employees in these retiring titles. 
As per our analysis on the employee data there are 1549 employees who qualify for mentorship eligibilty criteria.

# Conclusion -
The good news is there is existing employees within teh organization who can be trained into the retiring totles and new emplyees can be hired for replacemnet of these 1549 positions.
Pewlett Hackard can make data driven decisions based on our analysis on how to hire/ train and mentor existing employees, the data also shows emplyees here are long term employees to the company.

