#  DermaClinic – Dermatology Clinic Management System

**DermaClinic** is a desktop application designed to streamline the daily operations of dermatology clinics. It allows staff to manage patients, appointments, consultations, prescriptions, services, billing, and reporting — all in one user-friendly interface.

>  Final project for the course: *Desktop Application Development*  
>  University of Economics Ho Chi Minh City – School of Technology & Design  
>  Instructor: *Mr. Le Huu Thanh Tung*  
>  Team project – Group 3

---

## Overview

This C# Windows Forms application automates various clinic workflows such as:

- Patient and staff management
- Appointment scheduling
- Medical examinations and prescriptions
- Service billing and receipt printing
- Statistical reports in PDF and Excel formats

---

## Project Documents

-  **Final report**: (https://docs.google.com/document/d/1wRvi-k0NkXiOzmVIT_a9aVrqkvR73fFX/edit?usp=drive_link)
-  **Presentation slides**: (https://drive.google.com/file/d/1zkdtVwfImhNgeCKaWBjJxEiqoHRcVy4I/view?usp=drive_link)

---

## Tech Stack

| Component     | Technology                             |
|---------------|----------------------------------------|
| Language      | C# (.NET Framework 4.7.2)              |
| UI Framework  | Windows Forms                          |
| Database      | SQL Server                             |
| ORM           | LINQ to SQL (.dbml)                    |
| Reporting     | RDLC ReportViewer, Crystal Reports     |

---

## How to Run

### Prerequisites

- Visual Studio 2022 or later
- SQL Server (any edition)
- SQL Server Management Studio (SSMS)
- RDLC Report Designer extension (for Visual Studio)
- Crystal Reports Runtime (SAP)

### Steps

1. **Clone this repository**:
   ```bash
   git clone https://github.com/NgTruc07/Derma_Clinic.git
   ```
   
2. **Initialize the database**:
   - Open SQL Server Management Studio
   - Run the SQL script in the `/Database/` folder to create the database

3. **Update the connection string** in `App.config`:
   ```xml
   <connectionStrings>
     <add name="DataClasses2ConnectionString"
          connectionString="Data Source=YOUR_SERVER;Initial Catalog=DataClasses2;Integrated Security=True;Encrypt=False;"
          providerName="System.Data.SqlClient" />
   </connectionStrings>
   ```
   Replace `YOUR_SERVER` with your actual SQL Server name (e.g., `.\SQLEXPRESS`)

4. **Open the solution file**:
   - Double-click `Clinix.sln` in Visual Studio
   - Build the solution
   - Press `F5` to run

---

## Default Login

- **Username:** `admin`  
- **Password:** `123`
---
## Project Status

- Completed and submitted as final coursework
- Functional and testable with sample data
- Documentation and source code are available publicly
---
## Notes

- This project is for educational purposes only.
- Please refer to the report and presentation for full feature details and screenshots.
