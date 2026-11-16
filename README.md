# 🏦Bank Account Management System (C++)

## Project Overview

This project is a menu-driven C++ application that simulates a simple banking system.

Users can create a bank account, deposit money, withdraw funds, check their balance, and display account details. The system includes input validation to ensure deposits and withdrawals follow banking rules.

The application allows users to perform multiple transactions until they choose to exit.

---

## 🎯Features

- Create a new bank account
- Capture account holder information
- Validate initial deposits
- Deposit money from an account
- Withdraw money from an account
- Prevent overdrawing
- Check current account balance
- Display account details
- Menu-driven navigation
- Input validation and error handling

---

## 🛠️Technologies Used

- C++
- Functions
- References
- Loops
- Conditional Statements
- Input Validation

---

## 📂Repository Structure

```text
bank-account-management-system-cpp/
│
├── BankAccountManagement.cpp
├── README.md
│
└── screenshots/
    ├── menu-output.png
    ├── deposit-withdrawal.png
    └── account-details.png
```

---

## 📋Banking Rules

The system enforces the following rules:

### Account Creation

The initial deposit must be greater than R0.

### Deposits

The deposit amount must be greater than R0.

### Withdrawals

- The withdrawal amount must be greater than R0.
- The withdrawal amount cannot exceed the available balance.

---

## ⚙️Functions Implemented

### createAccount()

createAccount(string &name,
              int &accountNumber,
              double &balance)

Responsibilities:

- Capture account holder name
- Capture account number
- Capture initial deposit
- Validate initial deposit amount

---

### depositMoney()

depositMoney(double &balance)

Responsibilities:

- Accept withdrawal amount
- Validate withdrawal amount
- Prevent overdrawing
- Update balance

---

### checkBalance()

checkBalance(const double &balance)

Responsibilities:

Display current account balance

---

### displayAccountDetails()

displayAccountDetails(
    const string &name,
    const int &accountNumber,
    const double &balance
)

Responsibilities:

- Display customer name
- Display account number
- Display account balance

---

## 🔄️Menu System

The application uses a loop-driven menu that repeatedly allows users to perform banking operations until they choose to exit.

## Menu Options
1. Create Account
2. Deposit Money
3. Withdraw Money
4. Check Balance
5. Display Account Details
6. Exit

---

## 📸Program Screenshots

### Main Menu

insert here

### Deposit and Withdrawals

insert here

### Account Details

insert here

---

## ✅Input Validation

The program validates:

- Invalid menu selections
- Negative deposits
- Zero deposits
- Negative withdrawals
- Zero withdrawals
- Withdrawals exceeding available balance
- Invalid initial deposit amounts

Example:

Error: Deposit amount must be greater than zero.

Error: Insufficient funds.

---

## ▶️Running the Program

### Compile

g++ BankAccountManagement.cpp -o BankAccountManagement

### Run
./BankAccountManagement

---

## 📚Concepts Demonstrated

This project demonstrates:

- Function Design
- Pass-by-Reference
- Input Validation
- Banking Logic
- Loops
- Menu Systems
- Conditional Statements
- Structured Programming
- User Interaction

---

## 🌟Learning Outcomes 

By completing this project, the following programming concepts were applied:

- Modular programming using functions
- Validation of user input
- Management of account balances
- Menu-driven application development
- Real-world business rule implementation

---

## 🔮Future Enhancements

- Multiple customer accounts
- PIN authentication
- Savings and cheque accounts
- Interest calculations
- Transaction history
- Data persistence using files
- Database integration
- Graphical User Interface (GUI)
