# Rice_Project_2
ETL Project for Rice Bootcamp

This contains the code used to create a MySQL database relating college and degree recorded salaries with some information about the colleges - including cost data, degree data, demographic data, and admissions data

Read full explanation [here](https://docs.google.com/document/d/1r9pAzCjvrznvfVVCcIehjgSsrL7fFV43xp9Q_C_2h7Q/edit?usp=sharing).


# If using the code:
- first, navigate into the Code folder and run create_db.sql to create the colleges_db database.
- second, in the Code folder, open config.py and include an API key for data.gov and a password for the MySQL connection used to create the database from the first step
- third, run the code contained in ETLNotebook.ipybn

This will result in three tables contained in colleges_db at your MySQL connection

Note that I have copied my colleges_db schema into the MySQL_schema folder, along with the three tables