# Intro to Table Relations in SQL

## Learning Goals

- Use primary and foreign keys to create the relations in a relational database.
- Use `INNER JOIN` and `LEFT JOIN` to retrieve relevant data for members of
  one table in other tables.
- Use joins to create one-to-many and many-to-many relationships between tables.

***

## Key Vocab

- **Primary Key**: a number that uniquely identifies one record in a table.
- **Foreign Key**: a column or group of columns that connects one table to
  another.
- **Join**: a query that returns related records from multiple tables in a
  single record.
- **One-to-Many**: a type of relationship between tables where one record in
  table A is connected to multiple records in table B. **e.g.** One person
  ordering multiple drinks at a bar.
- **Many-to-Many**: a type of relationship between tables where multiple
  records in table A are connected to multiple records in table B. **e.g.**
  Students have many classes and classes have many students.

***

## Introduction

The majority of databases you'll work with as a developer will have more than
one table, and those tables will be connected together in various ways to form
table relationships.

In this section we'll cover:

- The structure of a relational database as tables
- Primary key and foreign keys
- How to associate data tables using a foreign key column
- How to model **one-to-many** and **many-to-many** relationships
- How a join table is used
- Different types of joins

Over the next several lessons, we'll discuss having multiple tables in a
database, how to define relationships between different tables, and explain the
different types of table relationships that can exist.

***

## Resources

- [What is a Relational Database? - Google Cloud](https://cloud.google.com/learn/what-is-a-relational-database)
- [Difference between Primary Key and Foreign Key - GeeksforGeeks](https://www.geeksforgeeks.org/difference-between-primary-key-and-foreign-key/)
- [SQL Joins - W3Schools](https://www.w3schools.com/sql/sql_join.asp)
- [Airtable's guide to many-to-many relationships](https://support.airtable.com/hc/en-us/articles/218734758-Airtable-s-guide-to-many-to-many-relationships)
