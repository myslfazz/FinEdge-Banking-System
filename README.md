# FinEdge-Banking-System
FinEdge Banking System — A secure and efficient Internet Banking application built using Java, JDBC, and MySQL. It enables users to manage accounts, transfer funds, and view transaction history with robust authentication and role-based access control.

# 💳 FinEdge Banking System
<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg"/>
</p>

> 🏦 A secure and efficient Internet Banking System built using Java and MySQL, enabling users to manage accounts, transfer funds, and view transactions.

---

## 📚 Table of Contents
- [About](#-about)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Setup](#-how-to-run)
- [Screenshots](#-screenshots)
- [Future Enhancements](#-future-enhancements)
- [Author](#-author)

---

## 🧾 About
FinEdge Banking System is a Java-based simulation of an online banking platform that demonstrates **secure user management**, **transaction processing**, and **data persistence**.

---

## 🚀 Features
- 🔐 User authentication & authorization  
- 💸 Deposit, withdrawal, and transfer functionalities  
- 📊 Transaction history & account summary  
- 🧾 Admin control panel for user management  

---

## ⚙️ Tech Stack
- **Language:** Java  
- **Database:** MySQL  
- **UI:** Swing / JSP (optional)  
- **Build Tool:** Maven  

---

## 🗂️ Project Structure
FinEdge-Banking-System/
├── src/
│ ├── com/finedge/banking/
│ ├── dao/
│ ├── model/
│ ├── service/
│ └── ui/
├── database/
│ └── bank_schema.sql
└── README.md

---

## 🧩 How to Run
```bash
git clone https://github.com/myslfazz/FinEdge-Banking-System.git
javac -d bin src/com/finedge/banking/*.java
java -cp bin com.finedge.banking.Main


