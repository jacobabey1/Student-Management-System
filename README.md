Student Management System – VB.NET with MySQL & PDF Export
Assigments 2 – Practical Application Development

📌 Overview
This application is a desktop-based Student Management System built using Visual Basic .NET (Windows Forms) and connected to a MySQL database. It allows users to add, view, update, and delete student records (Name, Age, Course, Email) and generate a professional PDF report of all current records.

🛠️ Requirements
Software Dependencies:

Visual Studio 2022 (or newer) with .NET 6 / .NET Framework 4.7.2+
MySQL Server (8.0 recommended)
MySQL Workbench or phpMyAdmin (for database setup)
NuGet Packages (included in project):

MySql.Data – For MySQL connectivity
itext7 – For PDF generation
⚙️ Setup Instructions
1. Create the MySQL Database
Run the following SQL script in MySQL Workbench or phpMyAdmin:

sql
12345678910
💡 Note: The default connection uses root with no password. If your MySQL uses a password, update the connString in Form1.vb.

2. Open the Project in Visual Studio
Launch Visual Studio.
Open the solution file: Student Management System.sln
Restore NuGet packages if prompted.
3. Build and Run
Press F5 or click Start to run the application.
The main form will load with input fields and a data grid.
4. Generate PDF Report
Click "Generate PDF" to create StudentReport.pdf in the application’s output folder (e.g., bin\Debug\net6.0-windows).
The PDF includes a formatted table of all student records.
🖥️ Features
✅ Add Student – Enter name, age, course, and email.
✅ Update/Delete – Select any row in the grid to edit or remove.
✅ Real-Time Grid – Automatically refreshes after every operation.
✅ Input Validation – Ensures valid age (number), non-empty fields, and proper email format.
✅ PDF Export – Professional report with tabulated data (screenshots of UI are to be included separately in documentation).

📁 Project Structure
Form1.vb – Main form logic (CRUD + PDF)
Form1.Designer.vb – Auto-generated UI code
StudentReport.pdf – Sample output (generated at runtime)
Screenshots/ – (Included separately for submission)
📝 Notes for Submission
Screenshots of all operations (Add, Update, Delete, PDF) must be included in your documentation.
The PDF does not auto-embed screenshots — per project guidelines, include them manually in your report.
Ensure MySQL is running before launching the application.




Developer Jacob Abbey
STUDENT ID	400622038948
SEMESTER	SEMESTER VI
COURSE TITLE	ADVANCED VISUAL PROGRAMMING
DATE OF SUBMISSION	26-NOVEMBER 2025 
