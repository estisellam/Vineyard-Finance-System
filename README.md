# Winery Finance Management System

## Overview
A full-stack data-driven system for managing financial operations in a winery.

The project includes database design, data processing, business logic, and a graphical user interface, built on top of PostgreSQL.

---

## Key Features

- Relational database design using ERD and normalization  
- Complex SQL queries (SELECT, UPDATE, DELETE, aggregations)  
- Constraints and data integrity enforcement  
- Stored procedures, functions, and triggers (PL/pgSQL)  
- Data integration between multiple schemas  
- Graphical user interface built with Python (Tkinter)  
- Real-time data interaction with PostgreSQL  

---

## System Architecture

The system is composed of three main layers:

- **Database Layer**
  - PostgreSQL schema design
  - Tables, constraints, and relationships
  - Views for data abstraction

- **Logic Layer**
  - Stored procedures and functions
  - Business logic implementation
  - Data aggregation and validation

- **Application Layer**
  - Python GUI (Tkinter)
  - CRUD operations
  - Data visualization (matplotlib)

---

## Database Design

Includes:

- ERD (Entity Relationship Diagram)
- DSD (Database Schema Diagram)
- Multiple related entities such as:
  - Employees
  - Payments
  - Budgets
  - Investments
  - Purchases
  - Taxes
  - Salaries

![ERD](link_here)
![DSD](link_here)

---

## Advanced Database Features

### Queries
- Complex joins across multiple tables  
- Aggregations and grouping  
- Filtering and sorting with conditions  

### Transactions
- Use of `BEGIN`, `COMMIT`, `ROLLBACK`  
- Data consistency handling  

### Constraints
- NOT NULL  
- CHECK  
- DEFAULT values  

### Views
- Aggregated views for reporting  
- Business-oriented data abstraction  

---

## Stored Procedures and Functions

- Business logic implemented inside the database  
- Data aggregation and reporting  
- Parameterized functions returning dynamic results  

---

## Triggers

- Validation before insert operations  
- Automatic updates of summary tables  
- Real-time data consistency enforcement  

---

## Data Integration

- Merging schemas from different domains  
- Resolving conflicts between table structures  
- Maintaining consistency across integrated data  

---

## GUI Application

A desktop interface built with Python (Tkinter):

### Features:
- Employee management (CRUD)
- Salary management
- Tour management
- Payment summaries
- Data filtering and sorting
- Graph visualization (matplotlib)

### Screens:
- Main menu dashboard  
- Employee management  
- Salary management  
- Tour management  
- Summary reports  
- Data analysis graphs  

---

## Technologies

- PostgreSQL  
- SQL / PLpgSQL  
- Python  
- Tkinter  
- Matplotlib  
- Git / GitHub  

---

## Key Learnings

- Designing relational databases from scratch  
- Writing complex SQL queries and optimizing them  
- Implementing business logic in the database layer  
- Integrating multiple data sources  
- Building a full-stack data-driven application  
- Connecting a GUI to a live database system  

---

## How to Run

1. Setup PostgreSQL database  
2. Run SQL scripts to create schema and populate data  
3. Install Python dependencies  
4. Run the application:

```bash
python opening_screen.py
