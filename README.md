# Banking-Management-System
A C++-based Banking Management System designed using full Object-Oriented Programming principles, handling user clients, company accounts and employee controls. The system was later modernized into a React + TypeScript interface using AI-assisted refactoring, demonstrating both backend engineering and practical AI tool usag
🏦 Banking Management System

C++ Backend → AI-Assisted React/TypeScript Frontend

📌 Project Overview

This project is a Banking Management System developed as part of my Object-Oriented Programming (OOP) course.
The system is designed to help a bank efficiently manage user clients, company clients, and banking employees, handling real-world banking operations such as transactions, card management, fraud detection, and loan approvals.

The core system was implemented in C++ using full OOP principles. Later, the console-based interface was modernized into a React + TypeScript frontend using AI-assisted refactoring, while preserving the original business logic.

🎯 Objectives

Apply core OOP concepts: abstraction, encapsulation, inheritance, polymorphism, association, aggregation, and composition

Build a realistic banking system without hardcoding

Demonstrate backend engineering skills in C++

Showcase AI-assisted modernization by converting a console system into a modern UI

🧱 System Architecture
Backend (C++)

Object-oriented design with clear class hierarchy

File-based data persistence (no hardcoding)

Handles all business logic and validations

Frontend (React + TypeScript)

Modern UI for interacting with the system

AI-assisted refactoring of backend driver logic

Visual representation of cards, transactions, and account details

📌 Note: AI was used as a development tool to modernize the UI. All core logic, validations, and workflows were implemented and verified by me.

👥 Stakeholders & Features
1️⃣ User Client

Open a personal bank account

Deposit, withdraw, and transfer funds

View balance and transaction history

Assigned randomly generated 16-digit card numbers

PIN-based transaction verification

Multiple cards supported per user

Fraud detection after 3 incorrect PIN attempts

2️⃣ Company Client

Shared company account created by CEO

Multiple employees can access the same account

Deposit, withdraw, and transfer funds (to user clients only)

Request loans from the bank

Employee-to-company relationships maintained separately

3️⃣ Banking Employee (Admin)

Approve or reject new accounts

Approve or reject company loan requests

View all accounts and transaction histories

Freeze or close accounts in case of fraud

💳 Account Types
Account Type	Daily Withdrawal Limit	Eligible Clients
Bronze	100,000 PKR	User / Company
Gold	500,000 PKR	User / Company
Business	20,000,000 PKR	Company

Account type is automatically assigned based on estimated withdrawal limits.

💾 Data Management

All data is stored using file handling:

users.txt → User client details

companies.txt → Company account details

companies_employees.txt → Company–employee mapping

transactions.txt → Complete transaction history

cards.txt → Card numbers and PINs

admin.txt → Banking employee credentials

🧠 OOP Concepts Used

Abstraction – Clear separation of interfaces and implementations

Encapsulation – Secure data handling with access control

Inheritance – Different client and account types

Polymorphism – Unified transaction handling

Association & Aggregation – Users, companies, and cards

Composition – Accounts tightly coupled with transactions

🖥️ UI Showcase
Console Version (C++)

Demonstrates full backend logic

Handles all validations and workflows

Modern UI Version (React + TypeScript)

Interactive dashboard

Card visualization

Improved usability and presentation

📸 Screenshots included showing console output → modern UI transformation

🛠️ Technologies Used

C++ (Core backend & OOP design)

File Handling for persistence

React + TypeScript (Frontend)

AI-assisted refactoring for UI modernization

🚀 Key Takeaways

Built a complete real-world banking system as a 3rd-semester student

Strong foundation in backend engineering and OOP

Practical use of AI as a development accelerator

Experience in system design, validation, and modernization

📎 Future Improvements

Replace file handling with a database

Add real REST APIs between backend and frontend

Enhance UI animations and security layers
