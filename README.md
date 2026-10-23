# 🏦 Banking System

A Python-based Banking System project developed using Jupyter Notebook. It provides basic banking operations such as account creation, deposits, withdrawals, fund transfers, transaction history, and account statistics.

## About the Project

This project demonstrates how a simple banking management system works using Python. It uses object-oriented programming, exception handling, and file handling to manage bank accounts and transactions.

The notebook includes sample accounts for **Bhoopendra Singh, Aman Charnawat, Pawan, and Naman** to demonstrate the banking operations.

## Features

- Create new bank accounts
- Support for savings and current accounts
- View account details and balances
- Deposit and withdraw money
- Transfer funds between accounts
- Maintain transaction history
- Generate account summary statistics using NumPy
- Validate transactions and handle errors
- Save and reload account data using pickle
- Analyze transaction data using Pandas

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Pickle for data storage

## Installation and Setup

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
   ```

2. Open the project folder:

   ```bash
   cd YOUR-REPOSITORY
   ```

3. Install the required libraries:

   ```bash
   pip install numpy pandas notebook
   ```

4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `Banking_System_Modified.ipynb` and run the cells.

## How It Works

The system provides a menu-driven interface with options to create accounts, view account details, deposit money, withdraw money, transfer funds, check transaction history, view summary statistics, and exit the program.

It also demonstrates error handling for invalid amounts, insufficient balances, and invalid account numbers.

## Project Structure

```text
Banking-System/
│
├── Banking_Project.ipynb
├── README.md
└── bank_data.pkl       # Created when account data is saved
```

The data file is generated when the application saves account information. The notebook also uses a separate demo data file for sample operations.

## Learning Outcomes

- Understanding Python classes and objects
- Working with functions and custom exceptions
- Managing data using dictionaries and lists
- Reading and writing files
- Performing basic data analysis with NumPy and Pandas
- Implementing transaction validation and account management

## Note

This is an educational project created for learning and demonstration purposes. It is not a production-ready banking application and should not be used to store real financial information.

## Author

Bhoopendra Singh 
