# 💰 Project 09 — Expense Tracker

A beginner-friendly Python project that helps users manage their personal finances by recording income and expenses, categorizing transactions, generating monthly summaries, and saving records in a CSV file.

## 📌 Project Overview

The Expense Tracker is a menu-driven console application developed using Python and Object-Oriented Programming (OOP). It allows users to track their financial transactions and calculate their monthly savings.

The project demonstrates core Python programming concepts, including classes and objects, encapsulation, inheritance, abstraction, file handling, and exception handling.

## ✨ Features

- **Record Income:** Add salary, freelance earnings, and other sources of income.
- **Record Expenses:** Record daily spending such as food, transport, shopping, and bills.
- **Categorize Transactions:** Organize transactions by category.
- **View Transactions:** Display all saved income and expense records.
- **Monthly Summary:** Calculate total income, total expenses, and savings for a selected month.
- **Search Records:** Search transactions using category names or descriptions.
- **Persistent Storage:** Save transactions in a CSV file and load them when the application restarts.
- **Exception Handling:** Handle invalid amounts, incorrect dates, and file-related errors.

## 🛠️ Technologies Used

- Python 3
- Object-Oriented Programming (OOP)
- CSV file handling
- Python built-in modules: `csv`, `os`, `datetime`, and `abc`

## 📚 OOP Concepts Implemented

| Concept | Implementation |
|---|---|
| Classes and Objects | `Transaction`, `Income`, `Expense`, and `ExpenseTracker` |
| Encapsulation | Private attributes and getter/setter methods |
| Inheritance | `Income` and `Expense` inherit from `Transaction` |
| Abstraction | Abstract base class using the `abc` module |
| File Handling | Reading and writing transaction records using CSV |
| Exception Handling | Handling invalid input and file errors |

## 📂 Project Structure

```text
Project_09_Expense_Tracker/
│
├── expense_tracker.py
├── transactions.csv
├── screenshots/
│   └── expense_tracker.png
└── README.md
```

**Note:** `transactions.csv` is created automatically when the application saves records. The `screenshots/` folder is optional and can contain project screenshots or the project infographic.

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual repository URL.

### 2. Navigate to the project folder

```bash
cd Project_09_Expense_Tracker
```

### 3. Run the application

```bash
python expense_tracker.py
```

**Requirements:** Python 3 installed on your system. No external libraries are required.

## 🖥️ Application Menu

When you run the program, the following menu is displayed:

```text
================================
       EXPENSE TRACKER
================================
1. Record Income
2. Record Expense
3. View All Transactions
4. Monthly Summary
5. Search Transactions
6. Exit
================================
Enter your choice (1-6):
```

Enter the corresponding number to perform an operation.

## 💾 Data Storage

The application stores transaction records in `transactions.csv`, with the following fields:

- Transaction Type
- Amount
- Category
- Description
- Date

The CSV file allows saved records to be loaded again when the program restarts, provided the file remains available in the working directory.

## 📊 Example Use Case

Suppose a user records:

- Monthly salary: ₹28,000
- Grocery expenses: ₹1,200
- Transport expenses: ₹500

The monthly summary calculates:

- **Total Income:** ₹28,000
- **Total Expenses:** ₹1,700
- **Savings:** ₹26,300

These are illustrative figures to demonstrate the application's calculations.

## 🎯 Learning Outcomes

Through this project, I practiced:

- Designing classes and creating objects.
- Applying inheritance and abstraction in Python.
- Protecting attributes through encapsulation.
- Working with CSV files for persistent data storage.
- Using loops, conditional statements, and functions.
- Handling invalid inputs and file-related exceptions.
- Building a menu-driven console application.

## 🚀 Future Improvements

- Add transaction editing and deletion.
- Generate category-wise expense reports.
- Add budget limits and spending alerts.
- Display graphical spending charts.
- Develop a graphical user interface (GUI).

## 👩‍💻 Author

**Shriya Verma**

This project is part of my Python learning journey and practical portfolio, focused on strengthening programming fundamentals through real-world applications.

---

⭐ If you find this project useful, feel free to explore the code and suggest improvements.
