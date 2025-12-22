# Calenvisor - Administrative Advising Schedule Management System

## About
Calenvisor is a comprehensive admin interface designed for managing student advising schedules. This application empowers administrators to efficiently create,
read, update, and delete student appointment records across the entire advising ecosystem. 

## Features
_The application is built around five interconnected database tables, each with dedicated management capabilities._

### Students
Maintain the students' roster with CRUD functionality such as adding new students, updating existing records, or removing entries from the database as needed.

### Advisors
Manage your advising staff with the same comprehensive controls available for student records, including adding, editing, and removing advisor profiles.

### Locations
Configure and update appointment venues by specifying buildings and room assignments, ensuring accurate location tracking for all advising sessions.

### Availability 
View and manage all unscheduled appointment slots. Create new time slots, modify existing availabilities, and maintain an up-to-date calendar of open appointments. 

### Meetings
Schedule and assign students to their advising appointments. Define appointment types, add custom labels, and create the connections between students, advisors, and available time slots.

## Things to Set Up before running
### Execute the database
_The application requires a database backend. All necessary SQL files are located in the /backend/ directory (Populate and Procedures)_

### Running the Interface
There are two options for running the interface

### Option 1: Development Environment
Open and run the project using Visual Studio by loading the /B321_Project/ directory.

### Option 2: Standalone Executable
For direct execution without Visual Studio, navigate to: /obj/debug/B321_Project.exe.


## Architecture
Calenvisor provides a seamless administrative experience through its integrated five-table relational structure, ensuring data consistency and operational efficiency across all advising management workflows.
