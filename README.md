# 🚗 DVLD – Driver & Vehicle Licenses Department

A desktop application designed to simulate the operations of a **Driver & Vehicle Licenses Department (DVLD)**.

The project provides a complete system for managing people, drivers, driving licenses, applications, tests, and other license-related operations through a user-friendly Windows Forms interface.

---

## 📌 About The Project

**DVLD** is a desktop-based management system developed as a practical project to apply **Object-Oriented Programming, Database Management, and Software Architecture** concepts.

The application allows authorized users to manage and track different operations related to driving licenses and applicants in an organized way.

---

## ✨ Main Features

* 👤 **People Management**

  * Add, update, delete and search for people
  * Manage personal information

* 🚘 **Drivers Management**

  * Manage drivers
  * View driver information and related licenses

* 🪪 **Driving Licenses**

  * Issue and manage driving licenses
  * Renew licenses
  * Replace lost or damaged licenses
  * View license information

* 📝 **License Applications**

  * Create and manage applications
  * Track application status
  * Handle different application types

* 🧪 **Tests Management**

  * Manage vision, written and practical driving tests
  * Schedule tests
  * Record test results

* 🌍 **International Licenses**

  * Manage international driving licenses
  * Search and display license information

* 🔐 **Users & Permissions**

  * Manage system users
  * Authentication and user access

* 🔎 **Search & Filtering**

  * Search for people, drivers, applications and licenses
  * Display information in organized tables

---

## 🛠️ Technologies Used

| Technology               | Usage                     |
| ------------------------ | ------------------------- |
| **C#**                   | Main programming language |
| **.NET / Windows Forms** | Desktop application & UI  |
| **SQL Server**           | Database management       |
| **ADO.NET**              | Database connectivity     |
| **OOP**                  | Application architecture  |
| **Visual Studio**        | Development environment   |

---

## 🏗️ Project Architecture

The project follows a structured architecture that separates different responsibilities of the application.

```text
DVLD
│
├── Business Layer
│   └── Business logic and application rules
│
├── Data Access Layer
│   └── Database operations
│
├── Presentation Layer
│   └── Windows Forms
│
└── Database
    └── SQL Server
```

This separation makes the application easier to maintain, understand, and extend.

---

## 🗄️ Database

The application uses **Microsoft SQL Server** to store and manage system data.

The database contains information related to:

* People
* Drivers
* Users
* Licenses
* Applications
* Tests
* License classes
* International licenses

Database operations are handled using **ADO.NET**.

---

## 🎯 Project Goals

This project was developed to practice and strengthen practical programming skills, especially:

* Object-Oriented Programming
* C# and Windows Forms
* SQL Server
* Database design
* ADO.NET
* CRUD operations
* Multi-layer application architecture
* Data validation
* Working with relational databases
* Building real-world desktop applications

---

## 📸 Screenshots

*Add screenshots of the application here.*

Example:

```text
Main Dashboard
People Management
Drivers Management
Licenses Management
Applications Management
Tests Management
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/USERNAME/DVLD.git
```

### 2. Open the project

Open the solution file:

```text
DVLD.sln
```

using **Visual Studio**.

### 3. Configure the Database

* Create the SQL Server database.
* Execute the provided database script.
* Update the connection string according to your SQL Server configuration.

### 4. Run the Application

Build and run the project from Visual Studio.

---

## 📚 What I Learned

Working on this project helped me gain practical experience in building a complete desktop application from the database layer to the user interface.

It also improved my understanding of how **OOP, SQL Server, ADO.NET, and Windows Forms** can work together in a real-world application.

---

## 👨‍💻 Author

**Khalil Riad**

Student & Software Development Enthusiast

---

## ⭐ Support

If you find this project useful or interesting, feel free to ⭐ **star the repository**.

Thanks for checking out the project! 🚗💻
