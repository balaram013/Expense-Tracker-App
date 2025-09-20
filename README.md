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

Installation

Clone the repository:

git clone https://github.com/yourusername/expense-tracker.git
cd expense-tracker


Create a virtual environment:

# Windows
python -m venv venv
venv\Scripts\activate

# Linux/macOS
python3 -m venv venv
source venv/bin/activate


Install dependencies:

pip install -r requirements.txt


Note: Tkinter usually comes pre-installed with Python.

Usage

Run the app:

python main.py


Enter category, amount, and description to add a new expense.

Select an expense in the table and click Delete Selected to remove it.

The total expenses are shown at the bottom and update automatically.

Screenshots

(Optional: Add screenshots here)

Tech Stack

Python 3.x

Tkinter – GUI framework

SQLite – Local database

License

This project is licensed under the MIT License.
