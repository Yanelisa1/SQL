# SQL
WEEK
MODULE1: INTRODUCTION TO SQL

SQL which stands for Structured Query Language, is a standard programming language specifically designed for managing and manipulating relational databases. 
Requesting Data from a Database
SELECT Statement is used to retrieve data from a database. It allows you to specify which columns you want to retrieve data from. For example SELECT First_Name,Last_Name FROM Employees.
WHERE Statement is used  to filter records based on specified conditions. It allows you to retrieve only the rows that meet specific criteria. For Example SELECT * FROM customers WHERE city = 'New York'.
Statement Criteria uses the AND logical operator For Example "SELECT first_name, last_name FROM people WHERE state_code=CA AND shirt_or_hat=shirt." You can string multiple conditions with AND or even use OR to get results that meet one of two conditions. Just remember those parentheses they are your guiding light in complex queries.
Statement Responses Use the LIKE operator which allows us to look for values that match part of a field,Instead of a long OR statement, try 'state_code LIKE 'C%'.You can fine-tune your search with percent signs at different ends.If you want a specific number of results, throw in LIMIT. It helps when dealing with large databases.
The ORDER BY clause is used to sort the result set returned by a SELECT statement. It allows you to specify one or more columns by which to sort the rows, as well as the direction (ascending or descending) of the sorting.For Example SELECT * FROM products ORDER BY price DESC.
Finding More Data It is not just about matching records.Functions like LENGTH give us insights into field sizes. DISTINCT helps find unique values, and COUNT tallies records matching specific criteria.

MODULE1: Data Types And Arithmetic Operators

SQL Data Types
