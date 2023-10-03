# Ex. No: 5 Creating Triggers using PL/SQL

### AIM: To create a Trigger using PL/SQL.

### Steps:
1. Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);
2. Create salary_log table with following attributes (log_id NUMBER GENERATED ALWAYS AS IDENTITY, empid NUMBER,empname VARCHAR(10),old_salary NUMBER,new_salary NUMBER,update_date DATE);
3. Create a trigger named as log_salary-update.
4. Inside the trigger block, Insert the values into the salary_log table whenever the salary is updated.
5. End the trigger.
6. Update the salary of an employee in employee table.
7. Whenever a salary is updated for the employee it must be logged into the salary_log table with old salary and new salary.
8. Display the employee table, salary_log table.

### Program:
### Create employee table:
![image](https://github.com/gpavana/Ex-No-5-Creating-Triggers-using-PL-SQL/assets/118787343/8c7d11f7-9381-46ae-9e9c-cc5c16f9f8ab)

### Create salary_log table:
![image](https://github.com/gpavana/Ex-No-5-Creating-Triggers-using-PL-SQL/assets/118787343/06a11142-1441-4272-afe4-806aaa3c9d9d)

### PLSQL Trigger code:


### Output:


### Result:
A trigger is successfully created .
