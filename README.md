# Calenvisor – Administrative Advising Schedule Management System

## Overview

Calenvisor is an administrative scheduling system designed to manage student advising appointments across an academic environment.
The application enables administrators to create, update, and manage advising schedules while ensuring scheduling conflicts are prevented and relational data remains consistent.

This project was developed as a **collaborative academic project**.

## System Type
Desktop administrative application for advising schedule management.

**My Contributions**

* Designed backend domain models using **C# and .NET**
* Implemented database interaction utilities for **SQL Server**
* Enforced scheduling integrity through backend validation and database constraints to prevent double-booking
* Helped design the relational schema connecting students, advisors, locations, availability, and meetings

---

## Tech Stack

* **Language:** C#
* **Framework:** .NET
* **Database:** SQL Server
* **Development Environment:** Visual Studio
* **Architecture:** Object-oriented backend with database utility layer

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

Schedule advising sessions by connecting students, advisors, and available time slots. The system enforces validation rules to prevent scheduling conflicts.

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

The system separates application logic from database operations through a centralized database utility layer.
Backend validation and relational constraints ensure that advising appointments cannot be double-booked while maintaining referential integrity across the system.
