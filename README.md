## Common Terminologies
SQL (Structured Query Language) involves several key terminologies that are fundamental to understanding how to interact with databases. Here are some common terminologies used in SQL:

1. **Database**: A structured collection of data organized in a way that allows for efficient retrieval, storage, and manipulation. Examples include MySQL, PostgreSQL, SQL Server, Oracle Database, etc.

2. **Table**: A fundamental structure in SQL where data is stored. Tables consist of rows and columns, with each column representing a specific attribute of the data (e.g., `users` table with columns like `id`, `name`, `email`).

3. **Query**: A SQL statement used to retrieve, insert, update, or delete data from a database. Examples include `SELECT`, `INSERT`, `UPDATE`, `DELETE`.

4. **Schema**: A logical structure that defines the organization of data in a database. It includes the structure of tables, their columns, data types, constraints, relationships, etc.

5. **Primary Key**: A column or a set of columns that uniquely identifies each row in a table. It ensures that each row in a table can be uniquely identified and is often used as a reference point in relationships between tables.

6. **Foreign Key**: A column or a set of columns in one table that refers to the primary key in another table. It establishes a link between two tables, enforcing referential integrity and defining relationships.

7. **Index**: An optional structure associated with a table to improve the speed of data retrieval operations on that table. Indexes are created on columns that are frequently used in `WHERE` clauses to efficiently locate rows.

8. **Constraint**: Rules enforced on data columns to maintain the integrity and accuracy of the data. Examples include `NOT NULL`, `UNIQUE`, `PRIMARY KEY`, `FOREIGN KEY`, and `CHECK` constraints.

9. **Transaction**: A sequence of one or more SQL operations treated as a single unit of work. Transactions ensure data integrity by allowing operations to either complete entirely or be rolled back if an error occurs.

10. **View**: A virtual table generated from the result set of a SELECT query. Views can simplify complex queries, hide complexity, and provide a layer of security by restricting access to certain columns or rows.

11. **Stored Procedure**: A precompiled SQL code that can be stored and executed on the database server. Stored procedures can accept parameters, perform operations, and return results, offering performance benefits and security advantages.

12. **Normalization**: The process of organizing data in a database to minimize redundancy and dependency by dividing large tables into smaller tables and defining relationships between them.

These terminologies form the foundation of SQL and are essential for anyone working with databases or learning SQL programming. Understanding them helps in effectively designing, querying, and managing relational databases.
