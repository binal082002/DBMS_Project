# Hostel Management System – DBMS Project

## Project Overview

This project presents a **Hostel Management System** designed to streamline hostel operations by digitizing traditional paper-based records. It manages information related to students, rooms, fees, employees, mess services, internet, clubs, and more through a relational database model.

---

## Objective

To build an efficient and secure **database system** that handles all major aspects of hostel administration, including:
- Room allocations and availability
- Student and employee records
- Fee tracking and payment delays
- Mess and cleaning staff management
- Visitor logs
- Wi-Fi and club facilities

---

## Core Entities

- **Hostel & Buildings**  
- **Students**  
- **Rooms**  
- **Fees**  
- **Employees (Mess/Cleaning)**  
- **Mess Menu**  
- **Visitors**  
- **Internet (Wi-Fi)**  
- **Clubs**

Each entity is connected via clearly defined relationships, supporting constraints like one-to-one room allocation for students, department-specific employee access, and multi-member club participation.

---

## Sample Queries Implemented

- Students who haven't paid last month's fees  
- Vacant rooms by type and capacity  
- Employees earning more than department average  
- Visitors for specific students in a date range  
- Club participation filters (e.g., only dance, all clubs, none)  
- Mess menu under ₹100 for specific days  
- Wi-Fi router passwords by building  

Plus update and retrieval functions for:
- Student fee history
- Employee address

---

## Technologies Used

- **Database:** MySQL / Oracle SQL (assumed from context)
- **Design:** ER diagrams and normalized schemas (not shown here)
- **Language:** SQL (DDL, DML, queries, procedures/functions)

---

## Key Features

- Efficient student and room mapping  
- Automated fee status tracking (paid, unpaid, late)  
- Visitor check-in/check-out logs  
- Club and activity participation tracking  
- Department-wise employee access control  
- Integrated mess and internet facilities
