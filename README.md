# 🏦 Banking Management System

A simple, menu-driven **Banking Management System** developed in C++ using Object-Oriented Programming (OOP) concepts. This project allows users to create bank accounts, deposit and withdraw money, check balances, and manage account records.

## 👨‍💻 Project Details

- **Project Name:** Banking Management System
- **Language:** C++
- **Course:** B.Tech
- **Class:** CSE A
- **College:** CCE
- **Submitted By:** Deepanshu Mittal
- **Roll Number:** 2556446

## ✨ Features

- Create new bank accounts
- Support for Savings and Current Accounts
- Deposit money into an account
- Withdraw money from an account
- Check account balance
- Display individual account details
- Display all account records
- Prevent withdrawals when the balance is insufficient
- Save account and transaction records in files

## 🧠 OOP Concepts Used

- **Classes and Objects:** Organize banking operations and account information.
- **Encapsulation:** Keep account data and related functions together.
- **Inheritance:** Use Savings and Current Account classes derived from the base Account class.
- **Runtime Polymorphism:** Use overridden virtual functions for account-specific behavior.
- **Constructors:** Initialize account objects.
- **File Handling:** Store and retrieve account and transaction records.

## 🛠️ Technologies Used

- C++
- Object-Oriented Programming (OOP)
- File Handling (`fstream`)
- Standard Input/Output (`iostream`)

## 🚀 How to Run

1. Clone or download this repository.
2. Open the project folder in your C++ IDE or terminal.
3. Compile the source file using a C++ compiler.

   ```bash
   g++ main.cpp -o banking
   ```

4. Run the program.

   **Windows:**
   ```bash
   banking.exe
   ```

   **Linux/macOS:**
   ```bash
   ./banking
   ```

   Replace `main.cpp` with your actual C++ source filename if it is different.

## 📂 Project Structure

```text
Banking-Management-System/
│
├── main.cpp
├── accounts.txt
├── transactions.txt
└── README.md
```

*Note: The text files may be created by the program when records are saved. Adjust the filenames above to match your actual code.*

## 📸 Sample Operations

The program provides a menu to perform operations such as:

- Creating an account
- Depositing money
- Withdrawing money
- Viewing account details
- Checking insufficient-balance conditions

Add screenshots of your program output here to demonstrate these operations.

## 🎯 Objective

The main objective of this project is to understand the practical implementation of C++ OOP concepts and file handling by developing a basic banking application.

## 👤 Author

**Deepanshu Mittal**  
B.Tech — CSE A  
Roll No. 2556446  
College: CCE
