# Finals Lab Task 1. MySQL Basics Multi-Level Company
The following are the tasks that need to be implemented using MySQL statements. Make sure to complete them in the order specified:


## Task 1: Create a table named employees with the following fields:
employee id: Unique integer, auto-increment, primary key.
employee name: String (VARCHAR) with up to 255 characters, not null.
manager id: Integer, foreign key referencing employee id in the same table (employees).

## Task 2: Create a table named departments with the following fields:
department_id: Unique integer, auto-increment, primary key.
department_name: String (VARCHAR) with up to 255 characters, not null.

## Task 3: Create a table named employee departments with the following fields:
employee id: Integer, foreign key referencing employee id in employees.
department id: Integer, foreign key referencing department id in departments.
Composite primary key (employee id, department id).

## Task 4: Create a table named employee projects with the following fields:
employee id: Integer, foreign key referencing employee id in employees.
project name: String (VARCHAR) with up to 255 characters, not null.

## Task 5: Create a table named managers with the following fields:
manager id: Unique integer, auto-increment, primary key.
employee id: Integer, foreign key referencing employee_id in employees.



# Here's the Query Statement 

## 1. Employee Table.
![picture](https://github.com/Zomue/Zomue.github.io/blob/main/Image/1%20employees%20table.png)

## 2. Department Table.
![picture](https://github.com/Zomue/Zomue.github.io/blob/main/Image/1%20Department%20table.png)

## 3. Employee Dapartment Table.
![picture]()

## 4. Eployee Project Table. 
![picture]()

## 5. Manager Table. 
![picture]()




# Here's the Table Structure 

## 1. Employee Table.
![picture](https://github.com/Zomue/Zomue.github.io/blob/main/Image/1%20enployees%20table%201.png)

## 2. Dapertment Table.
![picture](https://github.com/Zomue/Zomue.github.io/blob/main/Image/1%20Department%20table%201.png)

## 3. Employee Dapartment Table.
![picture]()

## 4. Eployee Project Table. 
![picture]()

## 5. Manager Table. 
![picture]()

# ER Diagram 
![picture](https://github.com/Zomue/Zomue.github.io/blob/main/Image/1%20eer%20diagram%201.png)
