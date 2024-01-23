# SQL PROGRAMMING
___

## Lab program-5
**COMPANY DATABASE**

_Consider the schema for Company Database_ 📑

`EMPLOYEE` (SSN, Name, Address, Sex, Salary, SuperSSN, DNo) 

`DEPARTMENT` (DNo, DName, MgrSSN, MgrStartDate) 

`DLOCATION` (DNo,DLoc)

`PROJECT` (PNo, PName, PLocation, DNo)

`WORKS_ON` (SSN, PNo, Hours)


Write SQL queries to
1. Make a list of all project numbers for projects that involve an employee whose last name is
‘Scott’, either as a worker or as a manager of the department that controls the project.
2. Show the resulting salaries if every employee working on the ‘IoT’ project is given a 10
percent raise.
3. Find the sum of the salaries of all employees of the ‘Accounts’ department, as well as the
maximum salary, the minimum salary, and the average salary in this department
4. Retrieve the name of each employee who works on all the projects controlled by 
department number 5 (use NOT EXISTS operator). For each department that has more 
than five employees, retrieve the department number and the number of its employees 
who are making more than Rs. 6,00,000
