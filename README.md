#  Clinic Booking System (MySQL Database Project)

## MediTrac
**Clinic Booking System - Relational Database Design using MySQL**


##  Description

MediTrac implements a full-featured relational database to manage clinic operations such as:
- Patient records
- Doctor profiles and their specializations
- Booking appointments
- Treatment history
- Prescription management

The database enforces proper data integrity and models real-world relationships using primary keys, foreign keys, unique constraints, and many-to-many relationships via junction tables.


##  How to Run / Setup the Project

### Prerequisites:
- MySQL Server installed (e.g., MySQL 8+)
- MySQL Workbench or any SQL client

### Steps:
1. Clone or download the project folder.
2. Open the `clinic_booking_system.sql` file in MySQL Workbench.
3. Run the script to create all the necessary tables and constraints.

```bash
mysql -u your_username -p < clinic_booking_system.sql
