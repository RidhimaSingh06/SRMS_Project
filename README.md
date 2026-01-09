# SRMS_Project
“Student Result Management System in C with Dashboard UI”.
# 🎓 Student Result Management System (SRMS)

A **console-based Student Result Management System** with Dashboard UI developed in **C language**, designed for academic use to manage student records, results, attendance, and authentication with a clean and user-friendly interface.

---

## 📌 Features

### 🔐 Authentication
- Admin login with **hidden password input**
- Limited login attempts
- Password change functionality
- Secure password storage using file handling

### 👨‍🎓 Student Management
- Add new student records
- Display all students in formatted table
- Search student by:
  - Roll Number
  - Name
- Delete student record
- Automatic grade calculation

### 📊 Result Processing
- Marks-based **Grade system**
- **CGPA calculation**
- **Pass / Fail logic**
- Well-formatted result sheet output

### 🔃 Sorting Options
- Sort students by:
  - Name (A → Z)
  - Marks (High → Low)
  - Roll Number (Low → High)

### 🗓 Attendance Module
- Mark attendance (Present / Absent)
- View attendance report
- Attendance percentage calculation
- Admin-only access

### 🎨 Console UI Enhancements
- Colored text interface
- Structured menus
- Clean table formatting
- Professional exit message

---

## 🛠 Technologies Used

- **C Language**
- File Handling (`.txt` files)
- Windows Console API
- Dev-C++ / GCC Compiler

---

## 📁 File Structure
SRMS_PROJECT/
│
├── srms.c # Main source code
├── students.txt # Student records
├── attendance.txt # Attendance records
├── password.txt # Admin password storage
├── README.md # Project documentation

How to Compile and Run
[cite_start]This project uses system-specific libraries (conio.h, windows.h) for features like hidden password input and colored text, making it primarily compatible with Windows and compilers like MinGW/GCC (as indicated by the compiler details in the executable files [cite: 86]).

Prerequisites
[cite_start]A C compiler (e.g., GCC/MinGW, version 4.9.2 was used for the provided executables [cite: 86]).
A Windows operating system (for full functionality).
Steps
Compile the source code:
gcc srms_dashboard.c -o srms_dashboard.exe -m64
Run the executable:
./srms_dashboard.exe
🔐 Credentials (Default)
The system is initialized with a default administrator password.

User	Default Password	Role
admin	[cite_start]admin123 [cite: 1695]	Administrator (Full Access)
[cite_start]The first time the program runs, it will automatically create password.txt if it doesn't exist, containing the default password[cite: 1].
