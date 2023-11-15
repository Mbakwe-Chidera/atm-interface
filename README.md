# atm-interface

# Soma Bank ATM System

## Overview
This Python script simulates an ATM system for Soma Bank. It provides essential banking operations such as deposit, withdrawal, balance inquiry, transaction history viewing, and fund transfer. The program utilizes a `BankAccount` class to encapsulate account-related functionalities.

## Features
- **Account Operations:**
  - Create a new account with a name, account number, and PIN.
  - Secure PIN validation for account access.

- **Transaction Handling:**
  - Deposit funds with real-time balance updates.
  - Withdraw funds with PIN authentication and balance checks.
  - View account balance and transaction history.

- **Fund Transfer:**
  - Transfer funds securely between accounts.
  - Verify target account existence before initiating a transfer.

## Implementation Details
- The `BankAccount` class encapsulates account-related functionalities.
- Account information is stored in a global dictionary (`accounts`), allowing for easy retrieval and updates.

## Usage
1. Run the script to initiate the Soma Bank ATM system.
2. Create a new account or enter existing account details.
3. Choose from the menu options (Deposit, Withdraw, View Balance, View Transaction History, Transfer, Quit) to perform banking operations.
4. Follow on-screen prompts to complete transactions.

## Code Structure
- `BankAccount` class is responsible for managing account-related functionalities.
- The global dictionary `accounts` stores instances of `BankAccount` using account numbers as keys.

## Dependencies
- None, as the program is written in Python with standard libraries.

## Note
This program serves as a simple, educational ATM simulation and may require further enhancements for production use.

## How to Run
1. Clone the repository.
2. Ensure you have Python installed.
3. Run the script in a Python environment.

Feel free to explore the code, suggest improvements, and adapt it to suit your needs. Happy banking!

