# Calenvisor – Administrative Advising Schedule Management System

## Overview
Calenvisor is an administrative scheduling system for managing and coordinating student advising appointments in an academic environment. The system enables administrators to create, update, and manage schedules while enforcing business rules to prevent conflicts and maintain data integrity.

This project was developed collaboratively, with a focus on backend system design and scheduling logic.

## System Type
Desktop administrative application for advising schedule management.

## My Contributions

- Designed and implemented backend domain models using C# and .NET  
- Developed database interaction utilities for SQL Server using parameterized queries and stored procedures  
- Implemented backend validation logic and database constraints to enforce scheduling integrity and prevent double-booking  
- Contributed to relational schema design connecting students, advisors, locations, availability, and meetings
  
---

## Key Engineering Focus
- Backend development with C#/.NET and SQL Server  
- Designing and enforcing business logic for scheduling systems  
- Relational database modeling and data integrity  
- Preventing scheduling conflicts through application and database-level validation

---

## Tech Stack

* **Language:** C#
* **Framework:** .NET
* **Database:** SQL Server
* **Development Environment:** Visual Studio
* **Architecture:** Layered, object-oriented backend with centralized database utility layer

---

## Core Features

### Students

Maintain a roster of students with full CRUD functionality, allowing administrators to add, update, or remove records from the advising system.

### Advisors

Manage advisor profiles and maintain accurate records for staff responsible for advising appointments.

### Locations

Configure appointment venues including buildings and room assignments to ensure accurate scheduling information.

### Availability

Create and manage open advising time slots. Administrators can modify availability to maintain an accurate calendar of open appointments.

### Meetings

Schedule advising sessions by connecting students, advisors, and available time slots. The system enforces backend validation logic and database constraints to prevent scheduling conflicts and ensure consistency.

---

## Database Structure

The application is built on a **five-table relational schema**:

* Students
* Advisors
* Locations
* Availability
* Meetings

These tables are connected through relational constraints to ensure **data consistency and scheduling integrity**.

---

## Running the Application

### 1. Configure the Database

All SQL setup scripts are located in:

```
/backend/
```

Run the following scripts:

* Populate scripts
* Stored procedure scripts

---

### 2. Run the Application

**Option 1 — Development Environment**

Open the project in **Visual Studio**:

```
/B321_Project/
```

Run the application from the IDE.

**Option 2 — Standalone Executable**

Run the compiled executable:

```
/bin/Debug/B321_Project.exe
```

---

## Architecture Notes

The system separates application logic from database operations through a centralized database utility layer, improving maintainability and separation of concerns.  
Backend validation and relational constraints work together to enforce business rules, ensuring advising appointments cannot be double-booked while preserving referential integrity across the system.
