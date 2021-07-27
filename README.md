# Employee_Database_Analysis

![SQL](Instructions/sql.png)

## Data Engineering (use PostgreSQL)
•	Use the information you have to create a table schema for each of the six CSV files. Remember to specify data types, primary keys, foreign keys, and other constraints.
o	For the primary keys check to see if the column is unique, otherwise create a composite key. Which takes to primary keys in order to uniquely identify a row.
o	Be sure to create tables in the correct order to handle foreign keys.
•	Import each CSV file into the corresponding SQL table. Note be sure to import the data in the same order that the tables were created and account for the headers when importing to avoid errors.

## Data Analysis (use PostgreSQL)
Once you have a complete database, do the following:
1.	List the following details of each employee: employee number, last name, first name, sex, and salary.
2.	List first name, last name, and hire date for employees who were hired in 1986.
3.	List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.
4.	List the department of each employee with the following information: employee number, last name, first name, and department name.
5.	List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."
6.	List all employees in the Sales department, including their employee number, last name, first name, and department name.
7.	List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
8.	In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

## Visualization with Pandas (Jupyter Notebook)
1.	Import the SQL database into Pandas and use the code below to get started. Be sure to make any necessary modifications for your username, password, host, port, and database name:
    -- from sqlalchemy import create_engine
    -- engine = create_engine('postgresql://localhost:5432/<your_db_name>')
    -- connection = engine.connect()
•	Consult SQLAlchemy documentation for more information.
2.	Create a histogram to visualize the most common salary ranges for employees.
3.	Create a bar chart of average salary by title.
