# Travel-and-Tourism-Management
# 🧳 Travel and Tourism Management System

This Travel and Tourism Management System is a Java-based project designed to automate and streamline the process of booking travel packages and hotels, managing customer information, and improving the overall experience for both users and administrators.

---

## 📌 Project Overview

This system simplifies tourism operations by enabling:
- Seamless booking and cancellation of tour packages and hotels
- User registration and profile management
- Real-time access to destination and package information
- Secure and efficient database integration using SQL

It is built using **Java**, **MySQL**, **JDBC**, and integrates both GUI and CLI for different user needs.

---

## 🧰 Technologies Used

- **Frontend:** Java Swing (GUI)
- **Backend:** Java
- **Database:** MySQL
- **Connectivity:** JDBC (Java Database Connectivity)
- **Development Tool:** Eclipse IDE

---

## 📐 System Architecture

### ➤ Database Design

- Uses relational tables like `Account`, `Customer`, `BookPackage`, `BookHotel`, `Hotel`
- Implements SQL features such as:
  - **DDL (CREATE, ALTER, DROP)**
  - **DML (SELECT, INSERT, UPDATE, DELETE)**
  - **DCL (GRANT, REVOKE)**

### ➤ Stored Procedures and Triggers

- **Triggers** automate tasks (e.g., insert customer records on login).
- **Stored procedures** like `getCustomer` simplify and modularize data access.

---

## 🧩 Features

- User registration and login system
- Personal profile management
- Tour package and hotel booking
- Update and view customer details
- View travel destinations
- Integrated payment system simulation
- Admin and user panels

---

## 🧪 Testing

Implemented test cases to ensure:
- Valid login credentials
- Proper data insertion, updates, and deletions
- Error handling and message displays for invalid inputs

---

## 🖼️ Screenshots

> You can add screenshots here such as:
- Login page
- Booking page
- Package selection
- Customer update/view page
- Payment confirmation

---

## 🚀 How to Run

### Prerequisites
- Java JDK installed
- MySQL database setup
- Eclipse IDE (or any Java IDE)
- JDBC driver added to project classpath

### Steps

1. Clone this repository:
```bash
git clone https://github.com/yourusername/travel-and-tourism-management-system.git
