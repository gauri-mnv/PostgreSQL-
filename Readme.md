# PostgreSQL Basics – Hands-on Practice

## 📌 Overview

This repository documents my **hands-on practice of PostgreSQL Basics**, focusing on database creation, table design, CRUD operations, data types, and constraints. All screenshots below represent commands executed directly in **psql** and their outputs.

---

## 🧩 Topics Covered

* Database creation & deletion
* Switching between databases
* Table creation & schema inspection
* Data types & constraints
* CRUD operations (INSERT, SELECT, UPDATE, DELETE)
* Error handling & corrections
* Sequence functions (`currval`, `setval`)

---

## 🗄️ Database Operations

### Create Databases

![Create Database](https://i.ibb.co/zTQ1yqvj/db-create.png)
![Created Databases](https://i.ibb.co/1w1stVy/created-dbs.png)
![Multiple Databases](https://i.ibb.co/mVXh4Gc6/MNV-db.png)
![Person DB](https://i.ibb.co/MkyzdN0r/persondb.png)

### Switch & Drop Database

![Change Database](https://i.ibb.co/fGrd3kct/change-db.png)
![Drop Database](https://i.ibb.co/RXtJ3dz/drop-database.png)

---

## 📋 Table Creation & Schema

### Create Tables

![Employee Table Creation](https://i.ibb.co/RpC9YHm9/employee-cre.png)
![Employee Table](https://i.ibb.co/YBfWDThY/emp-table.png)
![Created Table](https://i.ibb.co/n22JMtZ/created-table.png)

### View Tables & Structure

![Show Tables](https://i.ibb.co/gZx2J2rn/tables.png)
![Show Data Table](https://i.ibb.co/q3NrGm3x/show-datatable.png)
![Describe Table](https://i.ibb.co/dwC0gYk3/describe-table-to-find-mistake.png)

---

## 🧱 Data Types & Constraints

### Data Types Usage

![Database Example](https://i.ibb.co/s9m2jf3Z/db2.png)

### Constraints & Validation

![Error Correction](https://i.ibb.co/DDDrTtzK/error-correction.png)

---

## ✍️ INSERT Operations (Create)

### Insert Data

![Insert Command](https://i.ibb.co/8LP986vf/Insert-comand.png)
![Insert Data](https://i.ibb.co/Q3HmwBz2/IN-data.png)
![Insert Multiple Rows](https://i.ibb.co/nMq0cxcM/multiple-row.png)
![Insert Example 2](https://i.ibb.co/gLgdYHJP/insert2.png)

---

## 🔍 SELECT Operations (Read)

### Fetch Data

![Select All](https://i.ibb.co/5XJ6fhhG/selectstar.png)
![Select Query](https://i.ibb.co/S4hNvLCw/select.png)
![Select Query 2](https://i.ibb.co/hx9QG6R4/select2.png)

### Conditional Queries

![IN Clause](https://i.ibb.co/Q3HmwBz2/IN-data.png)
![NOT IN Clause](https://i.ibb.co/gFrzJwQF/NOT-IN.png)
![Combined Conditions](https://i.ibb.co/6RxKY74z/combine.png)

---

## ♻️ UPDATE Operations

### Update Records

![Update Query](https://i.ibb.co/fzpxkYXw/update-query.png)
![Update Query 2](https://i.ibb.co/ccjKN84M/updateq2.png)
![Update Multiple Rows](https://i.ibb.co/vgMrzgv/update-multi.png)

---

## 🗑️ DELETE Operations

### Delete Records

![Delete Query](https://i.ibb.co/s9gPTRpf/delete.png)

---

## ⚠️ Errors & Corrections

### Common Errors and Fixes

![Error Example 1](https://i.ibb.co/DDDrTtzK/error-correction.png)
![Error Example 2](https://i.ibb.co/5hmkrGB4/error2.png)
![Error Example 3](https://i.ibb.co/Wv91HsZV/error3.png)

---

## 🔢 Sequences & Values

### Sequence Functions

![currval & setval](https://i.ibb.co/FqL99npw/current-val-setval.png)
![Different Sequence Value](https://i.ibb.co/1G5hW8gp/different-sub-val.png)

---

## 🛠️ Commands Practice Snapshot

![Commands](https://i.ibb.co/spsvgby4/commands.png)

---

## 👩‍💻 Contributor

**Gauri Bidwai**
PostgreSQL & Backend Learner

---

## ✅ Status

✔ PostgreSQL Basics Completed
📌 Next Work in Progress: PostgreSQL Advanced (Joins, Indexes, Transactions)


# 📘 PostgreSQL Advanced Concepts (Joins, Indexing & Transactions)

This section demonstrates hands-on practice of **PostgreSQL Advanced concepts** including joins, indexing, relationships, subqueries, and transactions with real execution screenshots.

---

## 🔹 SELECT Query

**Definition:**
The `SELECT` statement is used to fetch data from one or more tables.

![SELECT](https://i.ibb.co/S4hNvLCw/select.png)

---

## 🔹 Table Relationships

**Definition:**
Relationships define how tables are connected using primary and foreign keys.

### One-to-One / One-to-Many Relationships

![Relation](https://i.ibb.co/d0YBPSYW/rela1.png)
![Relation](https://i.ibb.co/Q7nRVG16/rel2.png)
![Relation](https://i.ibb.co/tM55T62D/rel4.png)
![Relation](https://i.ibb.co/4ZFBFPXM/rel5.png)
![Relation](https://i.ibb.co/RkZqZ6zd/rel6.png)

---

## 🔹 Many-to-Many Relationship

**Definition:**
A many-to-many relationship is implemented using a junction (mapping) table.

![Many to Many](https://i.ibb.co/5WDL1r8H/MANY-TO-MANY.png)

---

## 🔹 JOIN Operations

**Definition:**
Joins are used to combine rows from multiple tables based on related columns.

### INNER JOIN

Returns only matching records from both tables.

![Inner Join](https://i.ibb.co/k6564vJz/innerjoin.png)
![Inner Join](https://i.ibb.co/602yGHP5/Inner-Join1.png)

---

### LEFT JOIN

Returns all records from the left table and matching records from the right table.

![Left Join](https://i.ibb.co/tTtdD0j4/LEFTJOIN1.png)

---

### RIGHT JOIN

Returns all records from the right table and matching records from the left table.

![Right Join](https://i.ibb.co/99tbN1Yq/right-Join.png)

---

### CROSS JOIN

Returns the Cartesian product of both tables.

![Cross Join](https://i.ibb.co/TqkqfrCF/cross-join.png)

---

### JOIN Overview

![Join Overview](https://i.ibb.co/Q3FVhqvy/join.png)

---

## 🔹 CASE Statement

**Definition:**
The `CASE` statement is used to apply conditional logic in SQL queries.

![CASE](https://i.ibb.co/F4CnDHq9/case1.png)
![CASE](https://i.ibb.co/v6fCN03J/case2.png)
![CASE](https://i.ibb.co/gMdxJCM2/case4.png)
![CASE](https://i.ibb.co/CsTXqVKv/case5.png)

---

## 🔹 Subqueries

**Definition:**
A subquery is a query nested inside another query.

![Subquery](https://i.ibb.co/F4zj7XSN/subquery.png)

---

## 🔹 NOT IN Clause

**Definition:**
`NOT IN` is used to exclude records that match values from another query.

![NOT IN](https://i.ibb.co/gFrzJwQF/NOT-IN.png)

---

## 🔹 Indexing

**Definition:**
Indexes improve query performance by reducing data scan time.

![Indexing](https://i.ibb.co/CptmN5B4/Indexing.png)
![Index Example](https://i.ibb.co/7J1h3gKz/index2.png)

---

## 🔹 Transactions

**Definition:**
Transactions ensure data consistency by executing queries as a single unit (ACID properties).

![Transaction](https://i.ibb.co/6zPg09v/transaction.png)
![Transaction](https://i.ibb.co/k2TfhTrX/transaction2.png)


<!-- https://i.ibb.co/fGrd3kct/change-db.png
https://i.ibb.co/6RxKY74z/combine.png
https://i.ibb.co/spsvgby4/commands.png
https://i.ibb.co/1w1stVy/created-dbs.png
https://i.ibb.co/n22JMtZ/created-table.png
https://i.ibb.co/FqL99npw/current-val-setval.png
https://i.ibb.co/zTQ1yqvj/db-create.png
https://i.ibb.co/s9m2jf3Z/db2.png
https://i.ibb.co/s9gPTRpf/delete.png
https://i.ibb.co/dwC0gYk3/describe-table-to-find-mistake.png
https://i.ibb.co/1G5hW8gp/different-sub-val.png
https://i.ibb.co/RXtJ3dz/drop-database.png
https://i.ibb.co/YBfWDThY/emp-table.png
https://i.ibb.co/RpC9YHm9/employee-cre.png
https://i.ibb.co/DDDrTtzK/error-correction.png
https://i.ibb.co/5hmkrGB4/error2.png
https://i.ibb.co/Wv91HsZV/error3.png
https://i.ibb.co/Q3HmwBz2/IN-data.png
https://i.ibb.co/8LP986vf/Insert-comand.png
https://i.ibb.co/gLgdYHJP/insert2.png
https://i.ibb.co/mVXh4Gc6/MNV-db.png
https://i.ibb.co/nMq0cxcM/multiple-row.png
https://i.ibb.co/gFrzJwQF/NOT-IN.png
https://i.ibb.co/MkyzdN0r/persondb.png
https://i.ibb.co/S4hNvLCw/select.png
https://i.ibb.co/hx9QG6R4/select2.png
https://i.ibb.co/5XJ6fhhG/selectstar.png
https://i.ibb.co/q3NrGm3x/show-datatable.png
https://i.ibb.co/gZx2J2rn/tables.png
https://i.ibb.co/vgMrzgv/update-multi.png
https://i.ibb.co/fzpxkYXw/update-query.png
https://i.ibb.co/ccjKN84M/updateq2.png -->