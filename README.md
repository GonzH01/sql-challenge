# sql-challenge

**Overview**

  The database is designed to store and manage data about employees, their job titles, salaries, departments, and department managers. The structure is built using SQL and includes table creations and alterations for enforcing data relationships. Several SQL queries are provided to extract specific information from the database.

**Tables Schema**

  The database comprises 6 SQL tables designed to organize and manage employee-related information efficiently. One of the primary tables, "employees," stores comprehensive details about each employee, including their employee number, title ID, personal details such as name, birth date, and sex, along with their hire date. Another table, "dept_emp," serves to link employees with the departments they belong to, utilizing their employee number and department number for this purpose. Additionally, the "titles" table lists all possible job titles within the organization, recording both the title ID and the title name. Meanwhile, the "salaries" table records the salary for each employee, linking their employee number with the corresponding salary amount. The "dept_manager" table plays a crucial role in identifying which employees manage departments, indicated by their department number and manager's employee number. Lastly, the "departments" table provides details about each department in the organization, containing information such as department number and department name.

**SQL Queries**

  The first query retrieves specific details of employees alongside their corresponding salaries, including employee number, last name, first name, sex, and salary.The second query selects employee information, namely first name, last name, and hire date, for those hired in the year 1986. The WHERE clause effectively filters employees based on their hire date. The third query lists details of department managers, including the department number, department name, and manager's details. The fourth query is designed to fetch details of employees named Hercules whose last name starts with 'B,' including their first name, last name, and sex. The fifth query lists all employees within the Sales department. The sixth query, similar to the previous one, lists employees from both the Sales and Development departments. Lastly, the seventh query calculates the frequency of each last name among all employees.
