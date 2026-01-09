# E-Commerce MySQL Database Project

This project contains a simple MySQL relational database designed for an
e-commerce system.\
It includes tables for **customers**, **products**, **orders**, and
**order items**, along with several sample SQL queries and an ER-diagram
to visualize the schema.

## Table of Contents

-   Overview
-   Database Schema
-   Files Included
-   Installation
-   Tables Used
-   Sample Data
-   SQL Queries Included
-   ER Diagram
-   Usage
-   License

## Overview

This MySQL project simulates a basic e-commerce environment.\
It demonstrates: - Customer management\
- Product catalog\
- Order handling\
- Order item normalization\
- Common SQL queries used in database operations

The project is ideal for learning and teaching database fundamentals
such as joins, aggregations, normalization, and constraints.

## Files Included

-   **TABLES.TXT** -- SQL for tables and sample data.
-   **Queries.txt** -- SQL questions with solutions.
-   **DBdesign.png** -- ER diagram.

## Installation

### 1. Create the database

``` sql
CREATE DATABASE ecommerce;
USE ecommerce;
```

### 2. Run the table creation script

Paste the contents of TABLES.TXT into your MySQL console.

### 3. Verify tables

``` sql
SHOW TABLES;
```

## Tables Used

### customers

-   id\
-   name\
-   email\
-   address

### products

-   id\
-   name\
-   price\
-   description\
-   discount

### orders

-   id\
-   customer_id\
-   order_date\
-   total_amount

### order_items

-   id\
-   order_id\
-   product_id\
-   quantity

## Sample Data

Includes example customers, products, and orders as provided in
TABLES.TXT.

## SQL Queries Included

Contains queries for: - Recent customers\
- Total spent per customer\
- Updating product price\
- Adding columns\
- Top products\
- Many joins\
- Normalization steps\
- Avg totals\
- Finding customers who bought specific products

## ER Diagram

`DBdesign.png` represents the relationships visually.

## Usage

Suitable for SQL practice, database design learning, and backend
prototyping.

## License

Free to use and modify.
