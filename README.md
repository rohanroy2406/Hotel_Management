# 🏨 Hotel Management System

## 📌 Project Overview

The **Hotel Management System** is a desktop application developed in **Python** using the **Tkinter** library for the GUI and **SQLite** for database management. This system enables hotel staff to manage room bookings, customer information, check-ins, check-outs, and view customer details, all through an easy-to-use graphical interface.

---

## ✨ Features

- **Check-In System**: Register a new customer, assign a room number, and store their information.
- **Check-Out System**: Remove customer details once they check out.
- **Customer Information**: View the list of all current customers and their room numbers.
- **Room Information**: Retrieve full details of a customer by entering the room number.
- **Home Dashboard**: Navigate between various options using a simple menu interface.

---

## 🛠 Technologies Used

- **Python 3.x**
- **Tkinter** (GUI)
- **SQLite3** (Database)
- **Random** (For generating room numbers)

---

## 📁 Project Structure


Hotel-Management-System/
│
├── main.py               # Main launcher with the home UI
├── check_in_ui.py        # UI and logic for customer check-in
├── check_out.py          # UI and logic for customer check-out
├── customer_info.py      # UI for listing all customers
├── get_info.py           # UI for retrieving information by room number
├── Hotel.db              # SQLite database file
└── README.md             # Project documentation  

🚀 How to Run
Prerequisites
Python 3.x installed

Tkinter (pre-installed with Python)

SQLite3 (comes bundled with Python)

🧠 Future Improvements
Add billing and invoice generation.

Enhance room availability tracking.

Include login authentication for staff.

Upgrade UI with modern frameworks like PyQt or Kivy.
