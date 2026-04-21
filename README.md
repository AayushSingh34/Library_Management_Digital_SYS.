# 📚 Python Library Management System

![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)

A lightweight, terminal-based Library Management System built purely in Python. This project simulates a real-world library environment where administrators can manage book inventories, and users can issue and return books with a fully automated time-tracking and fine calculation system.

## ✨ Features

* **📦 Inventory Management:** Easily add new books and view the current available catalog.
* **🔄 Smart Issuing System:** Handles multiple copies of the same book and assigns unique IDs dynamically.
* **⏳ Automated Time Tracking:** Records the exact date a book is issued and automatically calculates a 15-day due date.
* **💰 Dynamic Fine Calculation:** Evaluates the return date against the issue date. If a book is overdue, it automatically calculates and imposes a daily fine.
* **🛡️ Data Integrity:** Ensures users can only return books that have actually been issued to them.

## 🛠️ Tech Stack

* **Language:** Python 3
* **Libraries:** `datetime` (Built-in)
* **Architecture:** Modular scripts (`main.py`, `add_books.py`, `issue_book.py`, `return_book.py`, `show_books.py`, `utils.py`) for clean, maintainable code.

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed on your system. You can check this by running:
`python --version`

### Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/YourUsername/your-repo-name.git](https://github.com/YourUsername/your-repo-name.git)
