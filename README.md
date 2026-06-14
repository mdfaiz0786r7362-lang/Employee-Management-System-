# Employee Management System (EMS)

## Overview

The Employee Management System (EMS) is a web-based application developed to manage employee information efficiently within an organization. The system helps administrators maintain employee records, track attendance, manage departments, process payroll information, and monitor employee performance through a centralized platform.

The primary goal of the system is to automate HR-related tasks, reduce manual paperwork, and improve organizational productivity.

## Features

* Employee Registration and Management
* Employee Profile Management
* Department and Designation Management
* Attendance Tracking
* Leave Management
* Payroll and Salary Management
* Employee Search and Filtering
* Performance Management
* Role-Based Access Control (Admin and Employee)
* Dashboard and Reports

## Technology Stack

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap

### Backend

* Python
* Django
* Django Rest

### Database

* MySQL

### Tools & Technologies

* Git & GitHub
* Maven
* Postman
* VS Code / IntelliJ IDEA

## System Modules

### Employee Module

Manages employee personal information, contact details, job roles, and department assignments.

### Department Module

Handles department creation, updates, and employee allocation.

### Attendance Module

Tracks employee attendance and working hours.

### Leave Management Module

Allows employees to apply for leave and administrators to approve or reject requests.

### Payroll Module

Maintains employee salary information and payroll records.

### Reporting Module

Generates employee reports, attendance summaries, and payroll reports.

## Project Structure

```text
EMS/
├── src/
├── controllers/
├── services/
├── repositories/
├── models/
├── resources/
├── templates/
├── static/
├── pom.xml
└── README.md
```

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/EMS.git
```

### 2. Navigate to Project Directory

```bash
cd EMS
```

### 3. Configure Database

Update the MySQL database credentials in the `application.properties` file.

### 4. Build the Project

```bash
mvn clean install
```

### 5. Run the Application

```bash
mvn spring-boot:run
```

### 6. Access the Application

Open your browser and visit:

```text
http://localhost:8080
```

## Database Tables

The system maintains data related to:

* Employees
* Departments
* Attendance
* Leave Requests
* Payroll
* Roles
* Users

## Benefits

* Centralized Employee Data Management
* Reduced Administrative Workload
* Improved Data Accuracy
* Better Employee Monitoring
* Efficient Payroll Processing
* Faster Report Generation

## Future Enhancements

* Employee Self-Service Portal
* Email Notifications
* Biometric Attendance Integration
* Mobile Application Support
* Performance Analytics Dashboard
* AI-Based HR Insights

## Author

Developed as part of an Employee Management System project to automate and simplify human resource management processes.

## License

This project is licensed under the MIT License.
