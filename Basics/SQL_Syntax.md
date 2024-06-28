# SQL Syntax

SQL syntax defines the rules for writing SQL statements. These statements are used to perform various operations on a database. Here are some key components of SQL syntax:

## Basic SQL Statements

- **SELECT**: Retrieve data from a database.
  ```sql
  SELECT column1, column2 FROM table_name;

INSERT
The INSERT statement is used to add new data to a database.

INSERT INTO table_name (column1, column2) VALUES (value1, value2);

UPDATE
The UPDATE statement is used to modify existing data in a database.

UPDATE table_name SET column1 = value1 WHERE condition;

DELETE
The DELETE statement is used to remove data from a database.

DELETE FROM table_name WHERE condition;

Clauses
FROM
Specifies the table from which to retrieve or manipulate data.

SELECT column1, column2 FROM table_name;

WHERE
Filters records based on specified conditions.

SELECT column1, column2 FROM table_name WHERE condition;

GROUP BY
Groups rows that have the same values in specified columns into summary rows.

SELECT column1, COUNT(*) FROM table_name GROUP BY column1;

HAVING
Filters groups based on specified conditions, often used with GROUP BY.

SELECT column1, COUNT(*) FROM table_name GROUP BY column1 HAVING COUNT(*) > 1;

ORDER BY
Sorts the result set in ascending or descending order.

SELECT column1, column2 FROM table_name ORDER BY column1 ASC;
SELECT column1, column2 FROM table_name ORDER BY column1 DESC;


Operators
  Comparison Operators
  =: Equal to
  <>: Not equal to
  >: Greater than
  <: Less than
  >=: Greater than or equal to
  <=: Less than or equal to
Logical Operators
  AND: Combines multiple conditions; all conditions must be true.
  OR: Combines multiple conditions; at least one condition must be true.
  NOT: Negates a condition.
Arithmetic Operators
  +: Addition
  -: Subtraction
  *: Multiplication
  /: Division
  %: Modulus
Functions
Aggregate Functions
  COUNT(): Returns the number of rows that match a specified condition.
  SUM(): Returns the total sum of a numeric column.
  AVG(): Returns the average value of a numeric column.
  MIN(): Returns the smallest value of a column.
  MAX(): Returns the largest value of a column.
String Functions
  CONCAT(): Concatenates two or more strings.
  LENGTH(): Returns the length of a string.
  SUBSTRING(): Extracts a substring from a string.
Date Functions
  NOW(): Returns the current date and time.
  CURDATE(): Returns the current date.
  DATEDIFF(): Returns the difference in days between two dates.

Example Query
Here's an example of a complex query that combines several of these elements:
SELECT name, age
FROM users
WHERE age > 25
ORDER BY age DESC;

In this query:

SELECT name, age retrieves the name and age columns from the users table.
FROM users specifies the table to retrieve the data from.
WHERE age > 25 filters the results to include only users older than 25.
ORDER BY age DESC sorts the results by age in descending order.
Understanding SQL syntax is crucial for writing effective SQL queries that can interact with the database in the desired manner.

CHAT GPT INTEGRATION - https://www.askyourdatabase.com/docs
