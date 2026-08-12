# Digital Wallet & Payment Management System (DWPMS)

## 📌 Project Overview

The **Digital Wallet & Payment Management System (DWPMS)** is an Advanced Database Management System project developed using **MySQL**. The system is designed to store and manage users, digital wallets, linked bank accounts, merchants, transactions, and payment requests.

The project focuses on database design, SQL operations, data integrity, transaction handling, and analytical queries.

## 🎯 Domain

**Digital Wallet & Payment Management / FinTech**

## 🛠️ Tech Stack

* **Database:** MySQL
* **Language:** SQL
* **Database Concepts:** DDL, DML, DQL, Joins, Subqueries, Aggregations, Views, Functions, Procedures, Transactions
* **Database Design:** ER Model, Relational Schema, Normalization up to 3NF

## 🗃️ Main Database Entities

The project contains six main tables:

1. `USERS`
2. `WALLETS`
3. `BANK_ACCOUNTS`
4. `MERCHANTS`
5. `TRANSACTIONS`
6. `PAYMENT_REQUESTS`

The database uses **Primary Keys, Foreign Keys, UNIQUE, NOT NULL, and CHECK constraints** to maintain data integrity.

## ⚙️ Key Features

* User and wallet registration
* Linking bank accounts
* Transfer money between wallets
* Merchant payments
* Payment requests
* Transaction management
* Suspicious transaction flagging
* User and merchant summary reports
* Wallet transaction analysis

These functional modules are part of the proposed system design.

## 📊 Database Operations

The project demonstrates:

* Database and table creation
* Data insertion, updating and deletion
* Basic SQL queries
* Aggregate functions such as `COUNT()`, `SUM()` and `AVG()`
* Multiple-table joins
* Nested queries and subqueries
* Views
* Indexing and query optimization using `EXPLAIN`
* User-defined functions
* Stored procedures
* Transactions with `COMMIT`, `ROLLBACK` and `SAVEPOINT`

A `Wallet_Transaction_Summary` view and `GetWalletTransactionCount()` function are also planned as part of the project.

## 🔐 Data Integrity & Transactions

The system uses database constraints and transaction handling to maintain consistency.

For wallet transfers, the debit and credit operations are treated as a single transaction. `COMMIT` is used when the operations succeed, while `ROLLBACK` is used when an error occurs.

## 🎓 Academic Context

**Course:** Advanced Database Management System Practical
**Institution:** Kristu Jayanti Institute of Technology
**Department:** Department of Computer Applications

## 👩‍💻 Author

**Lithiksha V**

---

### 📌 Project Status

**Academic Project – ADBMS**

The project will be developed, populated, tested and validated using MySQL and the concepts covered in the ADBMS practical.
