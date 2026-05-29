# Retail Transactions and Inventory Management Database

A SQL-based relational database project designed to manage retail products, manufacturers, customers, and sales transactions.

## Overview

This project demonstrates the design and implementation of a retail transaction and inventory management database using SQL. The database models relationships between manufacturers, products, customers, customer transactions, and the products included in each transaction.

The project focuses on core relational database concepts such as:

- Table creation
- Primary keys
- Foreign keys
- Composite keys
- Referential integrity
- Data insertion
- Table alteration
- Updates and deletes
- Relational design

## Technologies Used

- SQL
- Relational Database Management System
- SQL Server-style syntax

## Repository Structure

```text 
Retail_Transactions_and_Inventory_Management_Database/
├── Assignment4.sql
└── .gitattributes
```

## Database Relationships

```text
MANUFACTURERS
      |
      | one-to-many
      v
PRODUCTS_A4
      |
      | one-to-many
      v
PRODUCT_TRANSACTIONS_A4
      ^
      | one-to-many
      |
CUSTOMER_TRANSACTIONS_A4
      ^
      | one-to-many
      |
CUSTOMERS_A4
```
