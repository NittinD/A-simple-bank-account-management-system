# 🏦 Bank Account Management System (Python)

This is a simple console-based banking system built using Python and object-oriented programming concepts.

## 🔧 Features

- Create a bank account
- Deposit money
- Withdraw money
- Transfer funds to other accounts (including handling invalid recipients)
- Auto-generates transaction timestamps (India Standard Time)
- Friendly console interactions

## 🧠 Tech Stack

- Python 3
- `datetime` and `zoneinfo` for time tracking
- Object-Oriented Programming (OOP)

## 💡 How It Works

- Each customer is created as a `BankAcc` object.
- Deposits and withdrawals update the account balance.
- Transfers allow for valid and invalid recipients (money is deducted even for invalid targets with a warning).
- All actions include a timestamp for recordkeeping.

## 🚀 Future Improvements

- Add transaction history
- Support for account login/authentication
- GUI or web version
- Persistent storage (e.g., using a database or JSON)

## 📁 Getting Started

Clone the repo and run the script:

```bash
git clone https://github.com/yourusername/bank-system-python.git
cd bank-system-python
python bank.py
