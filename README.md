# Pewlett-Hackard Analysis
## Overview
In the coming years, a substantial number of employees will be retiring from Pewlett-Hackard. In order to deal with this exodus of staff, Pewlett-Hackard will need to hire and train a large contingent of replacement personnel. This analysis aims to identify where these retirements will pose the greatest risk/impact to the business, as well as identify a possible solution to the rapid loss of institutional knowledge.

## Results
 
* Pewlett-Hackard has over 72,000 employees who are eligible for retirement. These employees were all born between January 1 of 1952 and December 31 of 1955.

* According to the Employees table, there are currently a little over 300,000 Pewlett-Hackard employees. That means that if all retirement eligible employees retired in the next year Pewlett-Hackard would have to replace nearly a quarter of its employees.
  
* 25,000 of the potential retirees hold the title of Senior Engineer. A further 9,285 hold the title of Engineer, and another 1,090 hold the title of assistant engineer. Based on this list of retirees by title, the companies engineering capabilities are incredibly vulnerable to the coming retirements.

* A little over 1500 employees were born in 1965. If this is the only year taken for employees eligible to mentor new Pewlett-Hackard employees each mentor would have about 48 mentees.

Table 1: Retirement Eligible Employees by Department
| Eligible Staff Count| Title           |
| ------------- |:-------------:|
| 25,916      | Senior Engineer |
| 24,926      | Senior Staff      |
| 9,285 | Engineer      |
| 7,636      | Staff |
| 3,603      | Technique Leader      |
| 1,090 | Assistant Engineer      |
| 2      | Manager |

## Summary
There are 72,458 employees eligible to retire, meaning that over 70,000 positions will likely need to be filled in the coming 1-3 years. Using the current mentor eligibility of having a birth year of 1965, there are not enough employees to mentor the new employees that will be brought in to replace the retiring employees. 

The following two queries would be beneficial as leadership considers how to move forward.
1 How many employees have over ten years in the company? A query of the employees table looking for any employee with a hire date of over ten years ago may yield a much larger list of employees capable of mentoring new hires.
2 How many employees are eligible to begin receiving social security benefits? The birth date range of 1952 to 1955 gives us all of the employees who are age 67 to 70. There are likely many more employees who should be considered eligible for retirement. A new query of employees and their birth dates filtered to anybody born before 1960 would be a better list of employees eligible for retirement.

Although the coming years will pose a real challenge as Pewlett-Hackard faces a significant employee turnover, there is also an opportunity to modernize and adapt to the new business environment as a younger workforce takes the helm.
