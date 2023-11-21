
## SQL Challenge
### Description
Research Project about people whom the company employed during 1980s and 1990s uisng the 6 csv files
Task - Data Modeling, Data Engineering and Data Analysis
1. Design tables schema to hold data from the CSV files 
2. Import data from the tables to the SQL database 
3. Query the database

#### Data Modeling 
- Sketch the Entity Relationship Diagram from the tables - Using the QuickDBD tool, designed the table schema - 
- [
](https://github.com/supvadakkeveetil/sql-challenge/blob/main/EmployeeSQL/ERD_Employee.png)
#### Data Engineering
- Create table schema for the 6 csv files (Specify Datatypes, Primary Keys, Foreign Keys and other constraints) - Table_Schemata_Employee.sql
- Import the csv files into the SQL tables.

#### Data Analysis 
File - Queries_DataAnalysis_Employee.sql

1. List the employee number, last name, first name, sex, and salary of each employee.

2. List the first name, last name, and hire date for the employees who were hired in 1986.

3. List the manager of each department along with their department number, department name, employee number, last name, and first name.

4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

5. List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

6. List each employee in the Sales department, including their employee number, last name, and first name.

7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

## References
Data Source: As provided by Edx 
