# SmartLMS
Here’s your updated and complete **README** file for your project named **Smart LMS**, including all requested instructions:

---

# 📘 Smart LMS

## 📌 Introduction

**Smart LMS** (Smart Learning Management System) is a Windows-based application developed using **C# and WinForms in Visual Studio**. It is designed to simplify classroom interactions between students and teachers by providing tools to manage classes, share resources, submit assignments, track attendance, and communicate effectively within a digital environment.

---

## ✅ Features

* Student and Teacher Login/Registration
* Classroom Creation and Joining
* Uploading/Downloading Materials (Notes, Assignments, etc.)
* Assignment Submission and Teacher Grading
* Posting Announcements and Notifications
* Real-Time Chat Support
* Viewing Grades and Attendance
* Password Recovery Option
* Additional Tabs: Weekly Practice & Course Queries for Students

---

## 🏗️ Architecture

This project follows a **3-Tier Architecture**:

1. **Presentation Layer**

   * Built with Windows Forms (WinForms) for UI
   * Handles user interactions and events

2. **Business Logic Layer (BLL)**

   * Contains the core logic of the application
   * Handles validations, rules, and processes

3. **Data Access Layer (DAL)**

   * Manages file/database interactions
   * Reads/writes data for users, classrooms, and content

📌 **Justification**:
This architecture was chosen to promote **separation of concerns**, better **code maintenance**, **scalability**, and **ease of testing**.

---

## 🔧 How to Run the Project

1. **Download the ZIP File**
2. **Extract it to any folder on your PC**
3. Open the folder and locate the file with `.sln` extension (e.g., `SmartLMS.sln`)
4. **Double-click the `.sln` file** to open the project in **Visual Studio**

📌 **Note**:
Make sure you have the following installed in Visual Studio:

* **.NET Framework support**
* **Windows Forms (WinForms)** components

Then just **Build** and **Run** the project (`F5` or ▶️ button in Visual Studio)

---

## 📂 Folder Structure

```
/SmartLMS
│
├── BLL         # Business logic classes (Validations, Processing)
├── DAL         # Data access layer (Files, Storage)
├── Forms       # All WinForms UI (Login, Dashboard, Chat, etc.)
├── Models      # Data models (User, Assignment, Classroom, etc.)
└── SmartLMS.sln  # Solution file to launch the project
```

---

## ⚠️ Known Limitations

* Currently supports only local/offline use
* Basic chat and notification features
* Interface is kept simple for beginner-level interaction
* Limited role-based access customization

---

## 🚀 Future Improvements

* Add cloud/database integration for real-time sync
* Improve UI using modern UI libraries like Guna UI or Bunifu
* Add automatic reminders and notification scheduling
* Upgrade chat system with emojis, file sharing
* Implement advanced user roles (admin, TA, parent view, etc.)

---

## 👤 Author

*Saba Riaz,Nimra Saba
* Final Year Computer Science Student
* Project Duration: **March 1 – May 4, 2025**

---

 
