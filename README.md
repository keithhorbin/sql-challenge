## Background

Research project on employees of a corporation over two decades. The task is to recreate databases off of CSV records that exist for the corporation.

In this assignment, I had to understand the data files, learn how they are interrelated, diagram the relationships, design and build the Schema, import the CSVs into a SQL database, and answer some questions about the data. In short I performed:

1. Data Modeling

2. Data Engineering

3. Data Analysis

   

#### Data Modeling

- Inspect the CSVs and sketch out an ERD of the tables. 


#### Data Engineering

* Used the information at hand to create a table schema for each of the CSV files. Set data types, primary keys, foreign keys, and other constraints.
* Import the schema into pgAdmin to create the database and tables
* Import each CSV file into the corresponding SQL table.

#### Data Analysis

Queried the database for the following questions, approaches included joins, group by, order by, and extracts to derive accurate and meaningful results:

- List the following details of each employee: employee number, last name, first name, gender, and salary.
- List employees who were hired in 1986.
- List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name, and start and end employment dates.
- List the department of each employee with the following information: employee number, last name, first name, and department name.
- List all employees whose first name is "Hercules" and last names begin with "B."
- List all employees in the Sales department, including their employee number, last name, first name, and department name.
- List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
- In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.
- Import the SQL database into Pandas to conduct additional research and visualize some trends in the data.
- Create a histogram to visualize the most common salary ranges for employees.
- Create a bar chart of average salary by title.

## Files Uploaded

* Image of the ERD map for the database

* SQL file of the table schema

* SQL file of  the queries above

* Jupyter Notebook file of the import to pandas, additional analysis and charts


