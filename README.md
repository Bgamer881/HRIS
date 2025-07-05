
Human Resource Information System (HRIS)

## Project Overview

The **Human Resource Information System (HRIS)** is a comprehensive software solution designed to automate HR processes for small and medium enterprises (SMEs). Developed using Java Swing for the frontend and MySQL for the backend, this system streamlines employee management, attendance tracking, leave processing, and payroll calculation. It features role-based access control with distinct interfaces for administrators and employees, ensuring data security and operational efficiency.

---

## Key Features
- **Employee Management**: CRUD (Create, Read, Update, Delete) operations for employee records.
- **Attendance Tracking**: Daily recording of employee attendance (Present/Absent).
- **Leave Management**: Submission and approval workflow for leave requests.
- **Payroll Processing**: Automated salary calculation based on attendance records.
- **Reporting**: Generation of attendance reports and PDF payslips.
- **Security**: Role-based access control (Admin/Employee) with password authentication and encryption.

---


## Technologies Used
- **Frontend**: Java Swing (GUI)
- **Backend**: MySQL 8.0 (Database)
- **Libraries**: 
  - JFreeChart (for reporting)
  - Apache PDFBox (for PDF payslip generation)

---

## Installation and Setup
1. **Prerequisites**:
   - XAMPP (for MySQL database server)
   - Java Development Kit (JDK) installed.
   - MySQL Server installed and running.
   - MySQL Connector/J for Java-MySQL integration.

3. **Database Setup**:
   - Create a MySQL database named `hris_db`.
   - Import the provided SQL schema to set up tables and relationships.

4. **Run the Application**

## Testing
- **Unit Testing**: JUnit tests for CRUD operations (100% success rate).
- **Performance Testing**: Response time under 2 seconds for most operations.

---

## Future Enhancements
- Web-based platform for remote access.
- Performance appraisal module.
- Employee self-service portal.
- SMS/email notifications for leave approvals.
- Integration with accounting software.


