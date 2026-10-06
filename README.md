# 🏦 Bank Management System

A Java-based desktop banking application that simulates core ATM and account-management operations using **Java Swing, AWT, JDBC, and MySQL**.

> **Author:** Disha Kokane  
> **Project:** Bank Management System  
> **Academic Year:** 2024–2025

---

## 📌 Project Overview

The **Bank Management System** is a desktop-based application developed to simulate essential banking and ATM operations through a user-friendly graphical interface.

The system allows users to create new bank accounts, authenticate using a card number and PIN, deposit and withdraw money, check account balance, view recent transactions, perform fast cash withdrawals, and change their PIN.

The project demonstrates the practical implementation of **Java programming, GUI development, JDBC connectivity, MySQL database management, authentication, and transaction processing**.

---

## ✨ Key Features

- 🔐 Card Number & PIN-based Login
- 📝 Multi-step Account Registration
- 💳 Automatic Card Number & PIN Generation
- 💰 Initial Deposit
- ➕ Cash Deposit
- 💸 Cash Withdrawal
- ⚡ Fast Cash
- 📊 Balance Enquiry
- 🧾 Mini Statement
- 🔑 PIN Change
- 🚪 Secure Exit
- 🗄️ MySQL Database Integration
- 📋 Transaction Record Management

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| **Java** | Core application development |
| **Java Swing** | Graphical User Interface |
| **Java AWT** | GUI components and event handling |
| **JDBC** | Database connectivity |
| **MySQL** | Data and transaction storage |
| **Eclipse** | Development environment |

---

## 🏗️ Main Modules

### 1. User Authentication

Existing users can access the banking system using their:

- Card Number
- PIN

New users can proceed with account registration.

### 2. Account Registration

The signup process collects:

- Personal information
- Additional information
- Account information

After successful registration, the system generates banking credentials.

### 3. Initial Deposit

New users can make their initial deposit after completing account creation.

### 4. ATM Dashboard

The main ATM interface provides:

- Deposit
- Cash Withdrawal
- Fast Cash
- Balance Enquiry
- Mini Statement
- PIN Change
- Exit

### 5. Transaction Management

Banking transactions are stored in the MySQL database and can be retrieved for viewing transaction history.

---

## 🔄 Application Workflow

```text
                 START
                   │
                   ▼
          Login / New Account
             ┌─────┴─────┐
             │           │
          Existing      New User
             │           │
             ▼           ▼
        Card + PIN   Account Signup
             │           │
             │      Initial Deposit
             │           │
             └─────┬─────┘
                   ▼
             ATM Dashboard
                   │
       ┌───────────┼────────────┐
       │           │            │
    Deposit    Withdrawal   Balance
       │           │            │
       ├────── Fast Cash        │
       │                        │
       ├──── Mini Statement ────┤
       │                        │
       └────── PIN Change ──────┘
                   │
                   ▼
                  EXIT
```

---

## 🗃️ Database

The project uses **MySQL** for persistent data storage.

Major tables documented in the project include:

- `signup`
- `signuptwo`
- `signupthree`
- `login`
- `bank`

The database stores user information, authentication information, account details, and transaction records.

---

## 💻 System Requirements

### Software Requirements

- JDK 8 or above
- Eclipse IDE
- MySQL Server
- JDBC Driver
- Java Swing / AWT

### Hardware Requirements

- Dual Core processor or higher
- Minimum 4 GB RAM
- At least 500 MB free disk space
- Keyboard and mouse
- Standard display

---

## 🚀 How to Run

### Step 1 — Clone the Repository

```bash
git clone <YOUR-REPOSITORY-URL>
```

### Step 2 — Open the Project

Open the project in **Eclipse** or a compatible Java IDE.

### Step 3 — Configure Java

Make sure JDK 8 or above is installed.

### Step 4 — Configure MySQL

Create the required database and tables according to the project's database design.

### Step 5 — Configure JDBC

Add the MySQL JDBC driver to the project.

Update the database connection details in the Java source code.

### Step 6 — Run

Run the application's main/login class.

> ⚠️ Never upload database passwords or other private credentials to GitHub.

---

## 📊 Learning Outcomes

This project demonstrates practical knowledge of:

- Java programming
- Object-oriented programming
- Java Swing
- Java AWT
- Event-driven programming
- JDBC
- MySQL
- Database design
- Authentication
- Transaction management
- GUI design

---

## ⚠️ Current Limitations

The current academic implementation has limitations such as:

- Local desktop deployment
- Limited advanced security mechanisms
- No integration with real banking infrastructure
- No external payment gateway integration
- Limited multi-user/network deployment
- No real-time banking synchronization

This application is intended as an **academic banking/ATM simulation**, not as production banking software.

---

## 🔮 Future Enhancements

Possible future improvements include:

- 🔐 Two-factor authentication
- 🔒 Advanced encryption
- 📱 Mobile application
- 🌐 Web-based banking interface
- 💳 UPI and payment integration
- 📧 Email/SMS transaction alerts
- 👨‍💼 Admin dashboard
- 📈 Advanced financial reports
- ☁️ Cloud database deployment
- 🔄 Automated backup and recovery
- 📋 Detailed audit logs
- 🤖 AI-powered customer assistance

---

## 👩‍💻 Author

**Disha Kokane**
MCA Student
Software Development & Academic Projects


---

⭐ **If you find this project useful, consider giving the repository a star!**
