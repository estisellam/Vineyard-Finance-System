# Winery Finance Management System

A financial management system for a winery, combining relational database design, SQL-based analytics, and a Python-based graphical interface.

---

## Overview

This project implements a data-driven system for managing financial operations within a winery.  
The system was designed from scratch, including database modeling, data population, complex queries, and integration with a graphical user interface.

It demonstrates strong emphasis on relational database design, data integrity, and database-driven business logic.

---

## Key Features

- Unified payment system (income, expenses, salaries, investments)
- Advanced SQL queries (joins, aggregations, filtering, grouping)
- Data integrity enforced using constraints and foreign keys
- Automated financial summaries using triggers and procedures
- Role-based employee system (guides, workers, admins)
- Graphical user interface built with Python (Tkinter)

---

## System Architecture

- Database: PostgreSQL  
- Business Logic: PL/pgSQL (functions, procedures, triggers)  
- Application Layer: Python  
- User Interface: Tkinter  

The system separates data storage, business logic, and presentation layers, while maintaining consistency and reliability through database-level enforcement.

---

## Database Design Highlights

- Central `payment` table for all financial operations  
- Separation of entities:
  - employees  
  - salaries  
  - purchases  
  - investments  
  - taxes  
- Use of foreign keys to maintain relationships  
- Normalized schema to reduce redundancy  
- Configurable tax system without requiring schema changes  

---

## Advanced Database Logic

- Stored procedures for generating financial summaries  
- Triggers for automatic updates (`summary_report`)  
- Views for analytical queries  
- Transaction management using COMMIT and ROLLBACK  

---

## Application Screens

### Main Menu
![Main Menu](https://github.com/estisellam/department-finance---winery/blob/main/DBProject/%D7%A9%D7%9C%D7%91%20%D7%94/selection_screen.png)

### Employee Management
![Employee Management](https://github.com/estisellam/department-finance---winery/blob/main/DBProject/%D7%A9%D7%9C%D7%91%20%D7%94/employee_management.png)

### Payment Summary
![Summary Report](https://github.com/estisellam/department-finance---winery/blob/main/DBProject/%D7%A9%D7%9C%D7%91%20%D7%91/summary_reports.png)

### Guides Analysis
![Guides](https://github.com/estisellam/department-finance---winery/blob/main/DBProject/%D7%A9%D7%9C%D7%91%20%D7%94/experienced_guides.png)

---

## How to Run

### Requirements

- Python 3.10+
- PostgreSQL

### Steps

1. Create and start a PostgreSQL database
2. Run the SQL scripts to create tables, constraints, and logic
3. Run the application:

```bash
python opening_screen.py
