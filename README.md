# WorkForce-Pro-Advanced-Employee-Work-Management-Application-
Advanced Employee &amp; Work Management System built with C# and PostgreSQL. Centralized platform for managing employees, tasks, projects, timesheets, leave requests, and performance evaluations.

# WorkForce Pro

**Advanced Employee & Work Management System (C# + PostgreSQL)**

---

## Project Overview

WorkForce Pro is a professional application designed to manage employees, projects, tasks, working hours, leave requests, performance reviews, user accounts, and audit logs in a centralized platform. Developed using **C# (.NET)** and connected to a **PostgreSQL** database, the system reflects real-world organizational workflows and enterprise-level software and database design principles.

---

## Features

* Employee, Department, Role, and Location management
* Project and Task creation and assignment
* Timesheet tracking for working hours
* Leave request management
* Performance evaluation system
* User authentication and role-based access
* System activity logging (AuditLog)
* Reporting and analytics

---

## Database Structure

The system uses the following tables, each mapping directly to a **C# class**:

1. Employee
2. Department
3. Role
4. Location
5. UserAccount
6. Project
7. Task
8. Assignment
9. Timesheet
10. LeaveRequest
11. PerformanceReview
12. Status
13. AuditLog

### Relationships

* Department 1:N Employee
* Role 1:N Employee
* Employee M:N Task (via Assignment)
* Project 1:N Task
* Employee 1:N Timesheet
* Employee 1:N LeaveRequest
* Employee 1:N PerformanceReview
* Status 1:N Project / Task
* AuditLog records all critical actions

---

## Real-World Scenario (User Experience)

A medium-sized IT company employs 40+ people across multiple departments. HR managers register employees and assign them to departments and roles. Project managers create projects and tasks and assign them to employees. Employees log in daily to view tasks, record working hours, and request leave. Managers review performance reports at the end of the month. All critical actions are stored in **AuditLog** to ensure transparency and accountability.

---

## Technologies Used

* C# (.NET 6/7)
* PostgreSQL
* Entity Framework Core / ADO.NET
* Git & GitHub
* ER Diagram (Crow's Foot Notation)

---

## Usage

* **HR Manager:** Add employees, manage departments and roles.
* **Project Manager:** Create projects and assign tasks.
* **Employee:** View assigned tasks, log working hours, request leave.
* **Admin:** Review performance, monitor logs, generate reports.

---

## Expected Outcomes

* Fully functional employee and work management application.
* Clean, maintainable C# code mapping directly to the database structure.
* Enterprise-level usability with auditing and reporting.

---

## Author

**Valdrin Bislimi**
Computer Science & Engineering Student
University of Mitrovica "Isa Boletini"

---

## License

MIT License
