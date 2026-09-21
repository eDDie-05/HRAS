# Hospital Registration and Appointment System (HRAS)

The **Hospital Registration and Appointment System (HRAS)** is a software system designed to simplify patient registration and appointment management in hospitals and healthcare facilities.

The system helps manage patient information, doctor information, appointments, and basic hospital registration activities in an organized and efficient way.

## Features

* Patient registration
* Patient information management
* Doctor registration
* Doctor information management
* Appointment booking
* Appointment scheduling
* Appointment cancellation
* Search patient records
* View appointment records
* Update patient information
* Delete records
* Simple user-friendly interface
* Organized record management

## Main Modules

### Patient Management

Allows hospital staff to:

* Register new patients
* View patient information
* Search for patients
* Update patient records
* Delete patient records

### Doctor Management

Allows authorized users to:

* Register doctors
* View doctor information
* Manage doctor details
* Search for available doctors

### Appointment Management

The appointment module allows users to:

* Book appointments
* Select a doctor
* Select an appointment date
* Select an appointment time
* View scheduled appointments
* Cancel appointments
* Update appointments

## Example Patient Record

```text
Patient ID     : P001
Name           : John Doe
Age            : 25
Gender         : Male
Phone          : +255 XXX XXX XXX
Department     : General Medicine
```

## Example Appointment

```text
Appointment ID : A001
Patient        : John Doe
Doctor         : Dr. Smith
Department     : General Medicine
Date           : 2026-09-21
Time           : 10:00 AM
Status         : Scheduled
```

## Technologies

Depending on the implementation, HRAS can be developed using:

* **Programming Language:** C / Python / Java / JavaScript
* **Database:** MySQL / PostgreSQL / SQLite
* **Interface:** Command Line or Graphical User Interface
* **Database Connectivity:** Appropriate database driver/API

## Project Structure

```text
HRAS/
│
├── src/
│   ├── main.[extension]
│   ├── patient.[extension]
│   ├── doctor.[extension]
│   └── appointment.[extension]
│
├── database/
│   └── database.sql
│
├── assets/
│
└── README.md
```

## System Workflow

```text
Start
  ↓
User Login
  ↓
Patient Registration
  ↓
Patient Information Stored
  ↓
Select Department
  ↓
Select Doctor
  ↓
Choose Date & Time
  ↓
Confirm Appointment
  ↓
Appointment Stored
  ↓
View / Update / Cancel
  ↓
End
```

## User Roles

The system can support different users:

### Administrator

* Manage system users
* Manage doctors
* Manage patients
* Manage appointments
* View system records

### Receptionist

* Register patients
* Book appointments
* Update patient information
* View appointments

### Doctor

* View assigned appointments
* View relevant patient information
* Update appointment status

## Learning Objectives

This project demonstrates:

* User input and validation
* Data structures
* Functions and modular programming
* Database management
* CRUD operations
* Searching and sorting
* Record management
* Appointment scheduling
* User authentication
* Basic system design

## Future Improvements

* Online patient registration
* SMS appointment reminders
* Email notifications
* Doctor availability management
* Electronic medical records
* Payment management
* Prescription management
* Patient portal
* Mobile application
* Role-based access control
* Appointment conflict detection
* Reports and analytics

## Installation

Clone or download the project:

```bash
git clone <your-repository-url>
cd HRAS
```

Follow the project-specific setup instructions for the selected programming language and database.

## Purpose

HRAS is designed as an **educational and practical software project** demonstrating how technology can be used to organize hospital registration and appointment processes.

## eDDie

**Hospital Registration and Appointment System (HRAS)**

Developed for educational and software development purposes.

## License

This project is intended for educational purposes.
