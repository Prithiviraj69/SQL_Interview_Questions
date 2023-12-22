# SQL_Interview_Question

## SQL Interview Questions
1. **[What is Database?](#q1-what-is-database)**
2. **[What is DBMS?](#q2-what-is-dbms)**
3. **[What is RDBMS? How is it different from DBMS?](#q3-what-is-rdbms-how-is-it-different-from-dbms)**
4. **[What is SQL?](#q4-what-is-sql)**
5. **[Difference between SQL and MySQL?](#q5-difference-between-sql-and-mysql)**
6. **[What are Tables and Fields?](#q6-what-are-tables-and-fields)**
7. **[What are Constraints in SQL?](#q7-what-are-constraints-in-sql)**
8. **[What is a Primary Key?](#q8-what-is-a-primary-key)**
9. **[What is a UNIQUE constraint?](#q9-what-is-a-unique-constraint)**
10. **[What is a Foreign Key?](#q10-what-is-a-foreign-key)**
11. **[What is a Join? List its different types.](#q11-what-is-a-join-list-its-different-types)**
12. **[What is a Self-Join?](#q12-what-is-a-self-join)**
13. **[What is a Cross-Join?](#q13-what-is-a-cross-join)**
14. **[What is an Index? Explain its different types.](#q14-what-is-an-index-explain-its-different-types)**
15. **[Difference between Clustered and Non-Clustered Index?](#q15-difference-between-clustered-and-non-clustered-index)**
16. **[What is Data Integrity?](#q16-what-is-data-integrity)**
17. **[What is a Query?](#q17-what-is-a-query)**
18. **[What is a Subquery? Types of Subqueries?](#q18-what-is-a-subquery-what-are-its-types)**
19. **[What is the SELECT statement?](#q19-what-is-the-select-statement)**
20. **[Common clauses used with SELECT query in SQL?](#q20-common-clauses-used-with-select-query-in-sql)**
21. **[UNION, MINUS, and INTERSECT commands?](#q21-union-minus-and-intersect-commands)**
22. **[What is a Cursor? How to use a Cursor?](#q22-what-is-a-cursor-how-to-use-a-cursor)**
23. **[Entities and Relationships? Types of Relationships?](#q23-entities-and-relationships-types-of-relationships)**
24. **[What is an Alias in SQL?](#q24-what-is-an-alias-in-sql)**
25. **[What is a View?](#q25-what-is-a-view)**
26. **[What is Normalization? Denormalization?](#q26-what-is-normalization-denormalization)**
27. **[TRUNCATE, DELETE, and DROP statements?](#q27-truncate-delete-and-drop-statements)**
28. **[Difference between DROP and TRUNCATE statements?](#q28-difference-between-drop-and-truncate-statements)**
29. **[Difference between DELETE and TRUNCATE statements?](#q29-difference-between-delete-and-truncate-statements)**
30. **[Aggregate and Scalar functions?](#q30-aggregate-and-scalar-functions)**
31. **[User-defined function? Types of User-defined functions?](#q31-user-defined-function-what-are-its-various-types)**
32. **[What is OLTP?](#q32-what-is-oltp)**

# Questions and Answers

### Q1. What is a Database?
   - A database is an organized collection of data, stored and retrieved digitally from a remote or local computer system.
   - Databases can be vast and complex, and such databases are developed using fixed design and modeling approaches.
   - [Back to Top](#sql-interview-questions)

### Q2. What is DBMS?
   - DBMS stands for Database Management System.
   - It is a system software responsible for the creation, retrieval, updation, and management of the database.
   - DBMS ensures that data is consistent, organized, and easily accessible by serving as an interface between the database and its end-users or application software.
   - [Back to Top](#sql-interview-questions)

### Q3. What is RDBMS? How is it different from DBMS?
   - RDBMS stands for Relational Database Management System.
   - In RDBMS, data is stored in the form of a collection of tables, and relations can be defined between the common fields of these tables.
   - Most modern database management systems like MySQL, Microsoft SQL Server, Oracle, IBM DB2, and Amazon Redshift are based on RDBMS.
   - The key difference from DBMS is the relational structure and the ability to define relationships between tables.
   - [Back to Top](#sql-interview-questions)

### Q4. What is SQL?
   - SQL stands for Structured Query Language.
   - It is the standard language for relational database management systems.
   - SQL is used for retrieving and manipulating structured databases with entities and relations between them.
   - [Back to Top](#sql-interview-questions)

### Q5. What is the difference between SQL and MySQL?
   - SQL is a standard language for retrieving and manipulating structured databases.
   - MySQL is a specific relational database management system (RDBMS) that uses SQL as its query language.
   - MySQL is one of many RDBMS options available, while SQL is a language used across various database systems.
   - [Back to Top](#sql-interview-questions)

### Q6. What are Tables and Fields?
   - A table is an organized collection of data stored in rows and columns.
   - Columns are referred to as fields, and rows are referred to as records.
   - Columns can be categorized as vertical, and rows can be categorized as horizontal.
   - [Back to Top](#sql-interview-questions)

### Q7. What are Constraints in SQL?
   - Constraints are rules specifying data conditions for tables in SQL.
   - Applied during table creation or using the ALTER TABLE command.
   - Types of constraints include NOT NULL, CHECK, DEFAULT, UNIQUE, INDEX, PRIMARY KEY, and FOREIGN KEY.
   - Constraints ensure data integrity and enforce specific rules on the data.
   - [Back to Top](#sql-interview-questions)

### Q8. What is a Primary Key?
   - The PRIMARY KEY constraint uniquely identifies each row in a table.
   - It must contain UNIQUE values and has an implicit NOT NULL constraint.
   - A table can have only one primary key.
   - [Back to Top](#sql-interview-questions)

### Q9. What is a UNIQUE constraint?
   - A UNIQUE constraint ensures that all values in a column are different.
   - Provides uniqueness for the column(s) and helps identify each row uniquely.
   - Unlike the primary key, multiple unique constraints can be defined per table.
   - [Back to Top](#sql-interview-questions)

### Q10. What is a Foreign Key?
   - A FOREIGN KEY refers to the PRIMARY KEY in another table.
   - Ensures referential integrity in the relation between two tables.
   - The table with the foreign key is the child table, and the referenced table is the parent table.
   - [Back to Top](#sql-interview-questions)

### Q11. What is a Join? List its different types.
   - The SQL Join clause combines records from two or more tables based on a related column.
   - Types of JOINs: INNER JOIN, LEFT (OUTER) JOIN, RIGHT (OUTER) JOIN, FULL (OUTER) JOIN.
   - [Back to Top](#sql-interview-questions)

### Q12. What is a Self-Join?
   - A self JOIN is a case where a table is joined to itself based on some relation between its own column(s).
   - Uses INNER JOIN or LEFT JOIN with a table alias to assign different names.
   - [Back to Top](#sql-interview-questions)

### Q13. What is a Cross-Join?
   - Cross join is the cartesian product of two tables included in the join.
   - The result contains the same number of rows as the cross-product of the two tables.
   - If a WHERE clause is used, it functions like an INNER JOIN.
   - [Back to Top](#sql-interview-questions)

### Q14. What is an Index? Explain its different types.
   - An index is a data structure providing quick lookup of data in a column or columns.
   - It enhances speed but comes with additional writes and memory.
   - [Back to Top](#sql-interview-questions)

### Q15. What is the difference between Clustered and Non-clustered index?
   - Clustered index modifies the way records are stored based on the indexed column.
   - Non-clustered index creates a separate entity referencing the original table.
   - Clustered index is used for fast retrieval, while non-clustered retrieval is relatively slower.
   - [Back to Top](#sql-interview-questions)

### Q16. What is Data Integrity?
   - Data Integrity ensures accuracy and consistency of data throughout its life-cycle.
   - It enforces business rules on data when entered into an application or database.
   - [Back to Top](#sql-interview-questions)

### Q17. What is a Query?
   - A query is a request for data or information from a database table or combination of tables.
   - It can be a select query or an action query.
   - [Back to Top](#sql-interview-questions)

### Q18. What is a Subquery? What are its types?
   - A subquery is a query within another query, used to restrict or enhance data queried by the main query.
   - Types: Correlated (refers to columns in the main query) and Non-Correlated (independent query).
   - Example queries:
     - SQL query to update "status" in "applications" from 0 to 1.
     - SQL query to select "app_id" in "applications" where "app_id" < 1000.
     - SQL query to fetch "app_name" from "apps" where "apps.id" is equal to the collection of "app_id".
   - [Back to Top](#sql-interview-questions)

### Q19. What is the SELECT statement?
   - SELECT operator is used to select data from a database in SQL.
   - The data returned is stored in a result table, known as the result-set.
   - Example query: `SELECT * FROM myDB.students;`
   - [Back to Top](#sql-interview-questions)

### Q20. What are some common clauses used with SELECT query in SQL?
   - Common SQL clauses used with SELECT:
     - WHERE: Filter records based on specific conditions.
     - ORDER BY: Sort records in ascending (ASC) or descending order (DESC).
     - GROUP BY: Group records with identical data.
     - HAVING: Filter records in combination with GROUP BY.
   - Example query: `SELECT * FROM myDB.students WHERE graduation_year = 2019 ORDER BY studentID DESC;`
   - [Back to Top](#sql-interview-questions)

### Q21. What are UNION, MINUS and INTERSECT commands?
   - UNION: Combines and returns the result-set of two or more SELECT statements.
   - MINUS: Removes duplicates from the result-set of the second SELECT query and returns filtered results from the first.
   - INTERSECT: Combines result-sets where records from one match the other and returns the intersection.
   - [Back to Top](#sql-interview-questions)

### Q22. What is Cursor? How to use a Cursor?
   - A database cursor is a control structure for traversing records in a database.
   - Cursors facilitate processing after traversal, like retrieval, addition, and deletion of records.
   - [Back to Top](#sql-interview-questions)

### Q24. List the different types of relationships in SQL.
   - One-to-One, One-to-Many & Many-to-One, Many-to-Many, Self-Referencing Relationships.
   - [Back to Top](#sql-interview-questions)

### Q25. What is an Alias in SQL?
   - An alias is a temporary name assigned to a table or column in an SQL query.
   - It can be used for obfuscation and is represented by the AS keyword.
   - [Back to Top](#sql-interview-questions)

### Q26. What is a View?
   - A view in SQL is a virtual table based on the result-set of an SQL statement.
   - Contains rows and columns like a real table, with fields from one or more real tables.
   - [Back to Top](#sql-interview-questions)

### Q27. What is Normalization?
   - Normalization organizes structured data efficiently in a database.
   - It involves creating tables, establishing relationships, and defining rules for consistency.
   - [Back to Top](#sql-interview-questions)

### Q28. What is Denormalization?
   - Denormalization is the reverse process, adding redundancy for performance.
   - Reduces overhead in query processing caused by an over-normalized structure.
   - [Back to Top](#sql-interview-questions)

### Q30. What are the TRUNCATE, DELETE, and DROP statements?
   - TRUNCATE: Deletes all rows from a table and frees the space.
   - DELETE: Deletes rows from a table based on a condition.
   - DROP: Removes an object (table) from the database.
   - [Back to Top](#sql-interview-questions)

### Q31. What is the difference between DROP and TRUNCATE statements?
   - DROP: Removes table along with associated relationships, constraints, etc.
   - TRUNCATE: Deletes all rows but retains table structure and associated elements.
   - [Back to Top](#sql-interview-questions)

### Q32. What is the difference between DELETE and TRUNCATE statements?
   - DELETE: Deletes rows from a table based on a condition, doesn't free space.
   - TRUNCATE: Deletes all rows and frees the space containing the table.
   - [Back to Top](#sql-interview-questions)

### Q33. What are Aggregate and Scalar functions?
   - Aggregate: Perform operations on a collection of values, return a single scalar value.
   - Scalar: Return a single value based on the input value.
   - [Back to Top](#sql-interview-questions)

### Q34. What is User-defined function? What are its various types?
   - User-defined functions are like functions in programming languages, accepting parameters and returning values.
   - Types: Scalar (returns a single value) and Table-Valued (returns a table).
   - [Back to Top](#sql-interview-questions)

### Q35. What is OLTP?
   - OLTP (Online Transaction Processing) supports transaction-oriented programs.
   - Ensures concurrency, often decentralized, designed for a large number of users conducting short transactions.
   - [Back to Top](#sql-interview-questions)
