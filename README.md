# Expense-Tracker-App
Expense Tracker is a desktop application built with Python, Tkinter, and SQLite, designed to help users manage their daily expenses in a simple and organized way. The app provides a clean and user-friendly interface to add, view, and delete expenses, while keeping track of total spending automatically.

# 💸 Expense Tracker

A **desktop application** built with **Python**, **Tkinter**, and **SQLite** that helps users manage and track their daily expenses. The app allows you to **add, view, and delete expenses**, while keeping a running total of all spending.

---

## Features

- **Add Expenses**: Enter category, amount, and description for each expense.  
- **Expense History**: View all recorded expenses in a table with columns: Category, Amount, Description, Date.  
- **Delete Expenses**: Select one or multiple expenses and delete them easily.  
- **Total Spending**: Displays the total money spent and updates automatically.  
- **Organized & Modular**: Code is structured into multiple files (`main.py`, `ui.py`, `logic.py`, `database.py`) for easy maintenance.  
- **User-Friendly Interface**: Clean layout with labeled sections and modern fonts for a professional look.

---

## Project Structure

expense_tracker/
│
├── main.py # Entry point to run the app
├── database.py # SQLite database functions
├── logic.py # App logic for adding/updating/deleting
├── ui.py # Tkinter UI layout
├── expenses.db # SQLite database file (created automatically)
├── requirements.txt # Project dependencies
└── README.md # Project documentation
