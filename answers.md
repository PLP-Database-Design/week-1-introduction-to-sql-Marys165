### 1. **Components of a DBMS (Database Management System)**

A **DBMS** is a software system that facilitates the creation, management, and manipulation of databases. The key components of a DBMS are:

- **Database Engine**: The core part of a DBMS that handles data storage, retrieval, and updates. It ensures the integrity of the data and handles queries and transactions.
  
- **Database Schema**: The structure of the database, which defines the tables, relationships, and constraints. It describes how the data is organized.

- **Query Processor**: This component interprets and executes SQL queries. It optimizes queries to ensure efficient retrieval and manipulation of data.

- **Transaction Management**: Ensures that database operations are executed reliably and adhere to the ACID properties (Atomicity, Consistency, Isolation, Durability). It also handles concurrency and recovery.

- **Data Dictionary**: A metadata repository that stores information about the database schema, tables, columns, constraints, and other data elements.

- **User Interface**: Provides an interface (either command-line or graphical) for users and administrators to interact with the DBMS.

### 2. **What is a Relational Database? Give 4 Examples.**

A **relational database** is a type of database that stores data in tables (also called relations). Each table consists of rows (records) and columns (attributes). Data in different tables can be related to each other using keys, typically a **primary key** and **foreign key**.

Examples of relational databases include:
1. **MySQL**: A widely-used open-source relational database management system.
2. **PostgreSQL**: An open-source, object-relational database system known for its extensibility.
3. **Oracle Database**: A commercial relational database system used in large enterprises.
4. **Microsoft SQL Server**: A relational database management system developed by Microsoft.

### 3. **Three Classifications of SQL**

SQL (Structured Query Language) can be classified into the following categories:

- **DML (Data Manipulation Language)**: SQL commands that deal with the manipulation of data. Examples: `SELECT`, `INSERT`, `UPDATE`, `DELETE`.

- **DDL (Data Definition Language)**: SQL commands that define the structure of the database, such as creating or altering tables and indexes. Examples: `CREATE`, `ALTER`, `DROP`.

- **DCL (Data Control Language)**: SQL commands that control access to data and database operations. Examples: `GRANT`, `REVOKE`.

### 4. **Difference Between Primary Key and Foreign Key**

- **Primary Key**: 
  - A primary key uniquely identifies each record in a table.
  - It cannot have null values.
  - Each table can have only one primary key.

- **Foreign Key**: 
  - A foreign key is a field in one table that is used to link to the primary key in another table.
  - It helps maintain referential integrity between tables.
  - A table can have multiple foreign keys.

### 5. **What is an Entity-Relationship Diagram (ERD)?**

An **Entity-Relationship Diagram (ERD)** is a visual representation of the entities (tables) in a database and the relationships between them. It helps in designing and structuring the database by showing how data is interconnected. ERDs include entities, attributes, and relationships, often represented as rectangles (for entities), ovals (for attributes), and diamonds (for relationships).

### 6. **Advantages of Relational Databases**

- **Data Integrity**: Relational databases enforce data integrity through constraints like primary keys, foreign keys, and unique constraints, ensuring consistent and accurate data.
- **Structured Query Language (SQL)**: SQL provides a powerful, standardized language for querying and manipulating data.
- **Normalization**: Data is organized to reduce redundancy and improve efficiency.
- **Flexibility**: Relational databases support complex queries and can be used for a wide range of applications.
- **ACID Compliance**: Relational databases adhere to ACID properties, ensuring reliable transaction processing.

### 7. **Four Types of Data Types Used to Store Data in Tables**

- **Integer**: Used to store whole numbers (e.g., `INT`, `BIGINT`).
- **Varchar/Text**: Used to store variable-length strings (e.g., `VARCHAR`, `TEXT`).
- **Date/Time**: Used to store date and time values (e.g., `DATE`, `DATETIME`, `TIMESTAMP`).
- **Float/Decimal**: Used to store floating-point numbers or precise decimal values (e.g., `FLOAT`, `DECIMAL`).

### 8. **Purpose of a Database Management System (DBMS)**

The primary purpose of a **DBMS** is to provide a system that facilitates the storage, retrieval, and management of data in a database. It ensures the integrity, security, and consistency of data while providing efficient ways to query and manipulate large amounts of data. A DBMS also manages database access, concurrency control, and backup and recovery operations, supporting multiple users and applications.
