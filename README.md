# Income Expense Tracker


The Income Expense Tracker is a Python application designed for efficient personal finance management. This project allows users to track income and expenses, view transaction history, and analyze financial data using Python's standard libraries. Transactions are stored locally in a CSV file, which is automatically created if it doesn't exist.

Features:
Add Transactions:

Users can add new income or expense entries directly through the terminal/console.
Transactions include customizable descriptions and amounts, stored securely in a CSV format.
View Transactions:

Provides detailed transaction history within specified date ranges.
Summarizes total income and expenses for the selected period.
Data Analysis:

Offers basic data analysis capabilities using Python's built-in functionalities.
Users can gain insights into spending patterns and financial trends based on transaction data.
How It Works:
Initialization:

Upon launch, the application checks for the existence of a CSV file to store transactions. If not found, it creates one automatically.
Adding Transactions:

Users input transaction details such as type (income or expense), amount, and description directly into the terminal.
Data is immediately recorded and appended to the CSV file for persistent storage.
Viewing Transactions:

Users specify a start and end date to retrieve transactions within that period.
The application reads from the CSV file and displays a detailed list of transactions along with computed totals.
Data Analysis:

Utilizes Python's capabilities to compute and present financial summaries, helping users track their financial health over time.
Technologies Used:
Python: Core programming language for application logic and data handling.
CSV: Simple file format used for storing transaction data, managed seamlessly by the application.
Command Line Interface (CLI): Interacts directly with users through terminal/console commands.

Getting Started:
To start using the Income Expense Tracker:

Clone the Repository:

Clone the repository to your local machine using the following command:
git clone https://github.com/anthonycarreon/MatplotLib_ExpenseIncomeTracker

Run the Application:
Navigate into the cloned directory and run the application using:
python main.py
Follow the prompts in the terminal to add transactions, view transaction history, and analyze financial data.