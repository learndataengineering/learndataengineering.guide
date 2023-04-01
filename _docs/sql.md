---
layout: page
title: Phase 1- SQL
permalink: /sql
---

### Prerequisites

- **RDBMS Concepts**

   [What is DBMS?](https://www.guru99.com/what-is-dbms.html)

   [Database Architecture in DBMS](https://www.guru99.com/dbms-architecture.html)

   [DBMS Schemas](https://www.guru99.com/dbms-schemas.html)

   [Relational Data Model in DBMS](https://www.guru99.com/relational-data-model-dbms.html)

   [ER Diagram](https://www.guru99.com/er-diagram-tutorial-dbms.html)

   [DBMS Keys](https://www.guru99.com/dbms-keys.html)

   [SQL Commands: DML, DDL, DCL, TCL, DQL](https://www.guru99.com/sql-commands-dbms-query.html)

   [Transaction Management in DBMS](https://www.guru99.com/dbms-transaction-management.html)

   [Relational Algebra in DBMS](https://www.guru99.com/relational-algebra-dbms.html)

### What is SQL?

SQL (Structured Query Language) is a [declarative language](https://en.wikipedia.org/wiki/Declarative_programming) for storing, manipulating and retreiving data in databases and many other data processing systems.

We write statement like queries in SQL to perform actions on the data in a data processing system.

Example: Query retreives all the records from a database table

```sql
SELECT * FROM <database_name>.<table_name> 
```

SQL offers a simple interface to interact with data without having to write lengthy programs in any programming language. This has served wide veriety of data roles from various backgrounds well over four decades.

### Why Data Engineers Need SQL?

Data engineering is a data aware role. Every data engineer functions as a data analyst first to understand the intricacies of the data. Data skills and domain knowledge about it is very crucial to this role.

Data engineering tools and processes have evolved quite a lot over the years. One tool kept its relevance through all these times i.e., SQL.

Since SQL offered a simple interface to deal with data, many data warehousing tools like [Hive](https://aws.amazon.com/big-data/what-is-hive/), [Snowflake](https://www.snowflake.com/en/), [BigQuery](https://cloud.google.com/bigquery), and query engines like [Apache Spark](https://spark.apache.org/) adopted SQL as one of their main interfaces.

SQL is used for DE tasks like

  1. Building data models
  2. Light-weight data cleaning
  3. Data transformations
  4. Data analysis and testing
  5. Building reports

Of course, SQL is not be-all and end-all solution for all data engineering tasks but it is arguably a very important skill in modern data engineering.

<!-- ### Types of Data in Data Engineering

Data in the data engineering domain can be broadly classified into [structured, semi-structured and unstructured](https://k21academy.com/microsoft-azure/dp-900/structured-data-vs-unstructured-data-vs-semi-structured-data/) data.

- **Structured**:

  - Data is arranged in rows and columns like a table
  - Each column can store a data of single datatype. Ex: Integer, String etc.
  - Data follows a strict format and it is widely used in performing analysis
  - SQL is predominently used to analyze this kind of data
  - Relational databases, csv files and etc., store this type of data

| ![Structured Data](../assets/img/sql.md/structureddata.png) |
|:--:|
| *[Structured Data](https://k21academy.com/microsoft-azure/dp-900/structured-data-vs-unstructured-data-vs-semi-structured-data/)*|

- **Semi-Structured**:

  - Data is loosely structured meaning it doesn't follow a standard structure.
  - JSON, XML data and data stored in key-value stores and graph databases

| ![Semi-structured Data](../assets/img/sql.md/semi-structureddata.png) |
|:--:|
| *Semi-structured Data*|

- **Unstructured**:

  - Data is not structured at all and doesn't follow any pre-defined data model.
  - Examples are video, audio, images, logs, and binary data files

| ![Unstructured Data](../assets/img/sql.md/unstructureddata.png) |
|:--:|
| *Unstructured Data*| -->

### Important SQL Topics

| ![Data Engineering Lifecycle](../assets/img/sql.md/SQLforDE.png) |
|:--:|
| *SQL Topics*|

1. Table/View Operations

   - `CREATE`
   - `ALTER`
   - `TRUNCATE`
   - `DROP`

2. Data Retrieval

   - `SELECT`, `DISTINCT`
   - `WHERE` clause with `IN`, `AND`, `OR`, `NOT`, `LIKE` and `BETWEEN`
   - `COUNT`, `SUM`, `MIN`, `MAX`, `AVG`

3. Data Manipulation

   - `INSERT`
   - `UPDATE`
   - `DELETE`
   - `MERGE`

4. Aggregations

   - `GROUP BY`
   - `ORDER BY`
   - `HAVING`

5. Joins

   - `INNER`
   - `LEFT`
   - `RIGHT`
   - `FULL OUTER`
   - `CROSS JOIN`
   - `ANTI JOIN`

6. Windows/Analytics functions

   - `SUM`, `COUNT`, `AVG`
   - `ROW_NUMBER`
   - `RANK`
   - `DENSE_RANK`
   - `LEAD`
   - `LAG`
   - `NTILE`

7. Set Operations

   - `UNION`
   - `MINUS`

8. Others

   - `CTE`
   - `UDF`
   - Stored Procedures

**Note:**
This is not the complete list of all the topics in SQL for data engineers. It covers only necessary topics.
