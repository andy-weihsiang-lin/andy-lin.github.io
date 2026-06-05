+++
title = 'Practical SQL - 0 Introduction'
date = 2026-06-04T19:40:18-04:00
+++



## What is SQL

SQL, *Structured Query Language*, is a widely used programming language for managing data and database systems.

You will benefit from using SQL to collect, modify, explore, and summarize data.


## History

A pari of IBM researchers first outlined the syntax for SQL (then called SEQUAL) in a 1974 paper, builing on the theoretical work of the British computer scientist Edgar F. Codd.

In 1979, a precursor to the database company Oracle (then called Relational Software) became thefirst to use the language in a commercial product.

Today, SQL still ranks as one fo the most-used computer languages in the world, and that's unlikely to change soon.

## Database Systems

There are choices of database systems, such as *PostegreSQL*, *MySQL*, or *Microsoft SQL Server*. 

Each implements its own variant of SQL, so there are some differneces in syntax.

The American National Standards Institute (ASNI) adopted a standard for SQL in 1986, followed by the International Organization for Standardization (ISO) in 1987. But the standard does not cover all aspects of SQL that are required for a database implementation. That leave each database system maker to choose how to implement features the standards does not cover, and no database maker currently claims to conform to the entire standards.

This book chooses to use the **PostgreSQL** database system for the following reason:
- It's free.
- It's availabel for Windows, macOS, and Linux operating systems.
- Its SQL implementation aims to closely follow the SQL standard.
- It's widely used, so finding help online is easy.
- Its geospatial extension, PostGIS, allows user to analyze geometric data and perform mapping functions and is often used with mapping software such as QGIS.
- It's available in cloud computing environment such as AWS and Google Cloud.
- It's a common choice as a data store for web apps, including those powered by the popular web framework Django.

---

Return to <a href = "/projects/practical-sql-main">Practical SQL</a>


