# 🏦 Bank Management System

<div align="center">

![C++](https://img.shields.io/badge/Language-C%2B%2B-blue?style=for-the-badge&logo=c%2B%2B)
![Console](https://img.shields.io/badge/Application-Console-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Learning Project](https://img.shields.io/badge/Project-Learning-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge)

*A console-based Bank Management System developed as part of my C++ learning journey.*

</div>

---

# 📑 Table of Contents

- [📖 Project Overview](#-project-overview)
- [🎯 Learning Objectives](#-learning-objectives)
- [✨ Features](#-features)
- [🧠 Concepts Implemented](#-concepts-implemented)
- [⚙️ Application Workflow](#️-application-workflow)
- [📂 Project Structure](#-project-structure)
- [💻 Technologies Used](#-technologies-used)
- [🚀 Getting Started](#-getting-started)
- [💡 Skills Demonstrated](#-skills-demonstrated)
- [📸 Screenshots](#-screenshots)
- [🔮 Future Improvements](#-future-improvements)
- [👨‍💻 Author](#-author)

---

# 📖 Project Overview

The **Bank Management System** is a console-based application developed using **C++** that simulates the core operations of a simple banking system.

The project enables users to manage clients, perform banking transactions, manage system users, authenticate logins, control user permissions, and store data using text files.

Rather than focusing on advanced technologies, this project emphasizes building a complete application using fundamental C++ programming concepts while following a modular and organized design.

It represents one of my larger C++ projects and demonstrates how multiple programming concepts can be combined into a practical real-world application.

---

# 🎯 Learning Objectives

The primary goal of this project was to strengthen my understanding of C++ by integrating the concepts I learned into one complete application.

Instead of studying programming topics individually, I wanted to understand how they interact within a larger software project.

Through building this application, I practiced:

- Designing larger console applications
- Organizing code into reusable functions
- Managing structured data
- Working with persistent file storage
- Implementing authentication systems
- Managing user permissions
- Building menu-driven applications
- Applying real-world programming logic

---

# ✨ Features

## 👥 Client Management

- View all clients
- Add new clients
- Update existing client information
- Delete clients
- Search for clients
- Display client information

---

## 💰 Banking Transactions

- Deposit money
- Withdraw money
- Display total balances
- Update client balances automatically

---

## 🔐 User Management

- User login system
- Add new users
- Update user information
- Delete users
- Search users
- Permission-based access control

---

## 💾 Data Storage

- Store client data in text files
- Store user data in text files
- Automatically load data when the application starts
- Automatically save changes after modifications

---

## 🛡 Security Features

- Login authentication
- Username/password validation
- Permission checking
- Restricted menu access

---

# 🧠 Concepts Implemented

| Concept | Description |
|----------|-------------|
| **Variables** | Used to store application data throughout the program. |
| **Functions & Procedures** | Organized the application into reusable modules with clear responsibilities. |
| **Structures (`struct`)** | Represented clients, users, and banking data in a structured format. |
| **Enumerations (`enum`)** | Improved readability by representing menu options and permission values. |
| **Vectors** | Managed dynamic collections of clients and users. |
| **File Handling (`fstream`)** | Stored and retrieved data from text files for persistent storage. |
| **Reading & Writing Files** | Saved application data between program executions. |
| **String Manipulation** | Processed and formatted user input and file data. |
| **Passing by Reference** | Improved performance and simplified data modification. |
| **Conditional Statements** | Controlled application decisions and validations. |
| **Loops** | Implemented menu navigation and repeated operations. |
| **Switch Statements** | Managed menu-driven user interactions. |
| **Modular Programming** | Divided the project into logical, maintainable functions. |
| **Menu-Driven Programming** | Built an interactive console interface. |
| **Data Validation** | Reduced invalid user input and improved reliability. |
| **User Authentication** | Verified user credentials before granting access. |
| **Permission Management** | Restricted features based on assigned permissions. |
| **CRUD Operations** | Implemented Create, Read, Update, and Delete operations for clients and users. |
| **Basic Banking Logic** | Simulated common banking operations such as deposits and withdrawals. |

---

# ⚙️ Application Workflow

```text
Application Starts
        │
        ▼
Load Client Data
        │
        ▼
Load User Data
        │
        ▼
Login Screen
        │
        ▼
Validate Username & Password
        │
        ▼
Permission Check
        │
        ▼
Main Menu
        │
        ├───────────────┐
        │               │
        ▼               ▼
 Client Menu      User Management
        │               │
        ├───────────────┤
        ▼               ▼
 Transactions      Permissions
        │
        ▼
Save Changes
        │
        ▼
Logout / Exit
```

---

# 📂 Project Structure

The project follows a modular design where each function is responsible for a specific task.

```text
BankManagementSystem/
│
├── Source.cpp
│
├── Login System
├── Main Menu
├── Client Management
├── Transactions
├── User Management
├── Permission System
├── File Handling
├── Data Validation
└── Utility Functions
```

This organization improves readability, maintainability, and makes future enhancements easier to implement.

---

# 💻 Technologies Used

| Technology | Purpose |
|------------|---------|
| C++ | Core programming language |
| Standard Library | Containers, utilities, strings, algorithms |
| fstream | Persistent data storage |
| Console Application | User interface |

---

# 🚀 Getting Started

## Prerequisites

- C++ Compiler (GCC, MSVC, MinGW, or Clang)
- Visual Studio, Visual Studio Code, Code::Blocks, or any C++ IDE

---

## Clone the Repository

```bash
git clone https://github.com/your-username/Bank-Management-System.git
```

---

## Compile

Using g++:

```bash
g++ Source.cpp -o BankManagementSystem
```

---

## Run

```bash
./BankManagementSystem
```

Or simply run the generated executable on Windows.

---

# 💡 Skills Demonstrated

This project demonstrates my ability to:

- Build complete console applications
- Design modular and maintainable code
- Work with structured data
- Implement file-based persistence
- Create authentication systems
- Implement role-based permissions
- Develop CRUD operations
- Apply data validation techniques
- Build menu-driven applications
- Solve programming problems using fundamental C++ concepts

Although this is a learning project, it represents a significant step in applying programming concepts within a larger and more realistic application.

---

# 📸 Screenshots

> *Screenshots will be added here.*

## Login Screen

```
[ Login Screenshot ]
```

---

## Main Menu

```
[ Main Menu Screenshot ]
```

---

## Client Management

```
[ Client Management Screenshot ]
```

---

## Transactions

```
[ Transactions Screenshot ]
```

---

## User Management

```
[ User Management Screenshot ]
```

---

# 🔮 Future Improvements

Possible future enhancements include:

- 🗄 Database integration (SQL Server or MySQL)
- 🔒 Password hashing and stronger authentication
- ⚠️ Improved error handling
- 🎨 Enhanced console user interface
- 📊 Banking reports and analytics
- 🧾 Transaction history
- 📅 Account statements
- 🏛 Support for multiple account types
- 🧱 Object-Oriented Programming (OOP) version
- 🖥 GUI version using a desktop framework
- 🌐 REST API integration
- 📝 Logging system
- 💾 Automatic backup and recovery

---

# 👨‍💻 Author

## Created by **Akram Alnowirah**

This project represents an important milestone in my **C++ learning journey**.

It demonstrates my ability to combine fundamental programming concepts into a complete console application while practicing modular programming, file handling, authentication, permission management, and basic banking logic.

As I continue learning software development, I plan to expand this project by applying object-oriented programming principles, integrating databases, and exploring graphical user interface development.

---

<div align="center">

### ⭐ If you found this project interesting, consider giving it a Star!

Thank you for visiting my repository.

</div>
