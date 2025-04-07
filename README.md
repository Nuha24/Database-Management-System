# Electricity Bill Management System

A comprehensive **Database Management System (DBMS)** project developed using **Oracle**, focused on managing electricity billing operations. This project includes a fully normalized database design, detailed schema, SQL queries, and PL/SQL programs.

---

## 📐 A. Entity-Relationship Diagram (ERD)
- A well-structured, normalized ERD is provided to ensure data integrity and avoid redundancy.
- It highlights the relationships between core entities like Admin, Customer, Billing, and more.

---

## 🧩 B. Database Schema

### Main Tables & Attributes:

- **ADMIN** (`A_ID`, `A_NAME`, `SALARY`, etc.)
- **ELECTRICITY_BOARD** (`E_ID`, `NOTE`, `ANNOUNCEMENT`, etc.)
- **CUSTOMER** (`C_ID`, `C_NAME`, `MOBILE`, `C_EMAIL`, etc.)
- **BILLING** (`B_ID`, `PAYMENT`, `DUE_AMOUNT`, etc.)
- **ONLINE_PAYMETHOD** (`O_ID`, `PAYMENT_DETAILS`)
- **FEEDBACK** (`F_ID`, `User_Complaints`, `Responses`)
- **ACCOUNT** (`AC_ID`, `ACCOUNT_STATUS`, `NOTIFICATIONS`)
- **INVOICE** (`I_ID`, `TAX`, `FIXED_CHARGE`, `PREVIOUS_READING`, etc.)

---

## 🧮 C. SQL Queries

- **DDL Queries**:  
  Create all necessary tables with appropriate data types and constraints.

- **DML/Select Queries Examples**:
  - List of admins earning over 20,000
  - Customers using electricity for business purposes
  - Users who paid their bills online
  - Subqueries to filter data (e.g., customers located in Dhaka)

---

## 🔁 D. PL/SQL Programs

- Updating salaries of specific admins
- Fetching feedback for selected customers
- Identifying employees within a salary range
- Retrieving detailed billing information for customers

---

This project is ideal for understanding relational database modeling, SQL/PLSQL programming, and real-world data handling scenarios in utility billing systems.
