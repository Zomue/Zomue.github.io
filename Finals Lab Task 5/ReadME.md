# Finals Task 5.
                                    Using SQL views and Stored Procedures 
                                      and Stored Functions
Instructions: 

## 1. To have an idea of how SQL views work, kindly read the lecture on SQL views and stored procedures, then you may try the following examples in MySQL Workbench: 
## 2. Start Xampp and MySQL Workbench – create or start a connection 
## 4. Open the democodes.sql, and you may try executing all the examples using the hrd.sql file

## 5. AFTER the practice codes…. Perform the required SQL statements of the ff: use inventory.sql for this.

## 6. Print screen the appropriate sql and output per item
CREATE A VIEW that will display the vendors_code, vendors name, product description p_indate, of all products with p_indate from 2002 onwards

CREATE a VIEW that will display all products whose price range is between 100-150

Create a VIEW that will COMPUTE for the (TOTAL_PRICE) of ALL PRODUCTS by getting the (P_ONHAND x P_PRICE) Sold by vendors with the following v_code (21344, 23119 and 24288)


CREATE a STORED PROCEDURE that WILL take a SINGLE PARAMETER and UPDATED the Name of Vendor ‘Bryson,Inc.’ to ‘Bryson and Co’.


CREATE A Function that will take 2 parameters(v_code and v_state) and display All the product description and price based on the parameters passed to the function

# SCREENSHOTS OF THE OUTPUT! 

![picture](https://private-user-images.githubusercontent.com/201302626/441704630-936efb6b-d2f6-4883-be4e-1c543882a7a6.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDcxMTg5NjQsIm5iZiI6MTc0NzExODY2NCwicGF0aCI6Ii8yMDEzMDI2MjYvNDQxNzA0NjMwLTkzNmVmYjZiLWQyZjYtNDg4My1iZTRlLTFjNTQzODgyYTdhNi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTEzJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUxM1QwNjQ0MjRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT05NDVhYjg5NGMxMGU3MjNiNDU5YzU3ZWZkMjdkYzVlN2IwZWRmOThjYjQ5NjVjMzg5NTA1MTdhMzA1MDA0YTIxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.aH0nJ-3Q-zv0yh-3mzNCsj8VlpdMEPC86PZNE1An8hc)


