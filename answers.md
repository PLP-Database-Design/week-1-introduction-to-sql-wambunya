### Question 1

Components of a Database Management System (DBMS): A Database Management System (DBMS) is a software system that provides an interface for managing databases. The main components of a DBMS include:

Database Engine: Manages the storage, retrieval, and updating of data in the database.
Database Schema: Defines the logical structure and organization of the data within the database.
Query Processor: Interprets and executes SQL queries to retrieve or manipulate data.
Transaction Management System: Ensures that the database remains consistent and intact by managing transactions.
Data Dictionary: A repository that holds metadata, such as table definitions and relationships between them.
Security Management: Provides user authentication and authorization to ensure secure access to the database.

### Question 2

A relational database is a type of database that organizes data into tables (relations) with rows (records) and columns (attributes). These tables are related to each other using primary and foreign keys. The relational model enables data to be stored in an efficient, structured way and allows for the use of SQL for querying and managing the data. Four examples of relational databases include:

- MySQL
- PostgreSQL
- Oracle Database
- Microsoft SQL Server

### Question 3

Three Classifications of SQL: SQL can be classified into three categories based on its functionality:

- Data Definition Language (DDL): Used to define and manage the structure of database objects such as tables and indexes. Examples of DDL commands are CREATE, ALTER, and DROP.
- Data Manipulation Language (DML): Deals with the manipulation of data within the tables. DML commands include SELECT, INSERT, UPDATE, and DELETE.
- Data Control Language (DCL): Manages permissions and access control. The primary DCL commands are GRANT and REVOKE.

### Question 4

Difference Between a Primary Key and a Foreign Key:

- A primary key is a unique identifier for each record in a database table. It ensures that each record in the table is unique and can be referenced uniquely. A primary key cannot have NULL values.
- A foreign key is a column or set of columns in a table that refers to the primary key in another table. It is used to establish relationships between tables and ensures referential integrity by making sure that the value in the foreign key column matches a valid primary key value in the referenced table.

### Question 5

An Entity-Relationship Diagram (ERD) is a visual representation of the entities (objects) in a database and the relationships between them. ERDs are used to design and model databases, showcasing how entities interact with each other. The entities are typically represented by rectangles, and the relationships are shown by diamonds or lines connecting the entities. ERDs help in planning and visualizing the structure of a database.

### Question 6

Advantages of Relational Databases:

- Data Integrity: Ensures that data is accurate and consistent through the use of primary and foreign keys.
- Flexibility: Relational databases allow for complex queries and the ability to join data from multiple tables.
- Scalability: They can handle large amounts of data and users, making them suitable for both small and large-scale applications.
- Security: Supports access control and user authentication, providing secure access to data.
- ACID Properties: Relational databases ensure that transactions are processed reliably with Atomicity, Consistency, Isolation, and Durability.

### Question 7

Four Types of Data Types Used to Store Data in Tables: Common data types used in relational databases include:

- INT: Stores integer numbers.
- VARCHAR: Stores variable-length character strings.
- DATE: Stores date values (e.g., 'YYYY-MM-DD').
- DECIMAL: Stores exact numeric values with fixed precision and scale, often used for financial data.

### Question 8

The purpose of a DBMS is to manage and organize data within a database, providing an interface for users to interact with the data. A DBMS ensures that data is stored efficiently, allows for data retrieval using SQL queries, enforces data integrity, and supports multi-user access. It also handles transaction management, backup, and recovery to protect the database from data loss. In summary, a DBMS allows for the efficient and secure management of data, providing a foundation for applications to interact with and process the data.
