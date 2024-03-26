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

SQL Data Types define the type of data that can be stored in a table column.SQL has a few categories to be aware of binary for ones and zeros, dates and times for temporal info, numbers for numeric values, and text for characters.
SQL Math Operators supports various mathematical operators that can be used in SELECT statements or any place in the SQL query where you can use a numerical expression.We've got various operators to play with addition, subtraction, multiplication, division, and modulo.Logical comparison operators, like greater than, less than, and equal to, can help filter results. 
Compound Select is used to combine the results of two or more SELECT statements into a single result set.Enter sub-queries or sub-selects – they help us focus on specific data sets. 
Transforming SQL Data refers to the process of converting or modifying data into a more desirable or useful format.If you want to change the case of a string there is LOWER for lowercase and UPPER for uppercase. 
Aliases are used to give a temporary name to a table or a column in a table. They are often used to make column names more readable.

WEEK
MODULE1: INTRODUCTION TO SQL DATABASES
Modifying or Adding Data

Adding Data to Tables to add data to a table, you use the INSERT INTO statement. there are two main ways to use this statement which are specifying columns explicity and inserting into all columns.
Modifying Table Data to modify existing data in a table, the UPDATE statement is used.The SET clause specifies the columns to be updated and the new values and the WHERE clause is critical as it determines which rows will be updated. Without a WHERE clause, all rows in the table would be updated.
Removing Table Data to remove data from a table, the DELETE statement is used.Like with UPDATE, the WHERE clause specifies which rows should be deleted. Without a WHERE clause, all rows in the table would be removed, which might not be what you want.

WEEK
MODULE2: INTRODUCTION TO MONGODB

MongoDB is a popular, open-source, NoSQL database management system that uses a document-oriented data model. Developed by MongoDB Inc., it falls under the category of NoSQL databases, which means it doesn't use the traditional relational database structures found in SQL databases like MySQL.
Relational DB vs MongoDB
Relational Databases exemplified by Oracle, Microsoft SQL Server, and MySQL,organize data into tables, with rows and columns often interconnected.
MongoDB, a NoSQL database uses diverse methods, such as JavaScript or HTTP, to query data. MongoDB's flexible document store is a key feature, where data is stored in documents rather than tables.MongoDB's advantages include a schema-less storage format, rapid speed, and straightforward scalability. Despite these benefits, there are also drawbacks.

DOCUMENTS AND COLLECTIONS
Creating a document







