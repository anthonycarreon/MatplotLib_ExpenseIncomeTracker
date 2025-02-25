# Income Expense Tracker

<!-- HTML content for README.md -->
<p>The Income Expense Tracker is a Python application designed for efficient personal finance management. This project allows users to track income and expenses, view transaction history, and analyze financial data using Python's standard libraries. Transactions are stored locally in a CSV file, which is automatically created if it doesn't exist.</p>

<h2>Features:</h2>

<ul>
  <li><strong>Add Transactions:</strong>
    <ul>
      <li>Users can add new income or expense entries directly through the terminal/console.</li>
      <li>Transactions include customizable descriptions and amounts, stored securely in a CSV format.</li>
    </ul>
  </li>

  <li><strong>View Transactions:</strong>
    <ul>
      <li>Provides detailed transaction history within specified date ranges.</li>
      <li>Summarizes total income and expenses for the selected period.</li>
    </ul>
  </li>

  <li><strong>Data Analysis:</strong>
    <ul>
      <li>Offers basic data analysis capabilities using Python's built-in functionalities.</li>
      <li>Users can gain insights into spending patterns and financial trends based on transaction data.</li>
    </ul>
  </li>
</ul>

<h2>How It Works:</h2>

<ol>
  <li><strong>Initialization:</strong>
    <ul>
      <li>Upon launch, the application checks for the existence of a CSV file to store transactions. If not found, it creates one automatically.</li>
    </ul>
  </li>

  <li><strong>Adding Transactions:</strong>
    <ul>
      <li>Users input transaction details such as type (income or expense), amount, and description directly into the terminal.</li>
      <li>Data is immediately recorded and appended to the CSV file for persistent storage.</li>
    </ul>
  </li>

  <li><strong>Viewing Transactions:</strong>
    <ul>
      <li>Users specify a start and end date to retrieve transactions within that period.</li>
      <li>The application reads from the CSV file and displays a detailed list of transactions along with computed totals.</li>
    </ul>
  </li>

  <li><strong>Data Analysis:</strong>
    <ul>
      <li>Utilizes Python's capabilities to compute and present financial summaries, helping users track their financial health over time.</li>
    </ul>
  </li>
</ol>

<h2>Technologies Used:</h2>

<ul>
  <li><strong>Python:</strong> Core programming language for application logic and data handling.</li>
  <li><strong>CSV:</strong> Simple file format used for storing transaction data, managed seamlessly by the application.</li>
  <li><strong>Matplotlib:</strong> Python library used for generating charts and visualizing financial data.</li>
  <li><strong>Command Line Interface (CLI):</strong> Interacts directly with users through terminal/console commands.</li>
</ul>

<h2>Getting Started:</h2>

<p>To start using the Income Expense Tracker:</p>

<ol>
  <li><strong>Clone the Repository:</strong>
    <ul>
      <li>Clone the repository to your local machine using the following command:</li>
      <code>git clone https://github.com/anthonycarreon/MatplotLib_ExpenseIncomeTracker.git</code>
    </ul>
  </li>

  <li><strong>Run the Application:</strong>
    <ul>
      <li>Navigate into the cloned directory and run the application using:</li>
      <code>python main.py</code>
      <li>Follow the prompts in the terminal to add transactions, view transaction history, and analyze financial data.</li>
    </ul>
  </li>
</ol>

<p>

<h2>Screenshots:</h2>

<!-- Replace `your-username` with your actual GitHub username and adjust paths as necessary -->
<img src="Images/Screenshot1.png" alt="Screenshot 1" width="600">
<p align="center"><em>Example of the application interface showing transaction input.</em></p>

<img src="Images/Screenshot2.1.png" alt="Screenshot 2" width="600">
<img src="Images/Screenshot2.2.png" alt="Screenshot 2" width="600">
<p align="center"><em>Example of the application interface displaying transaction history and analysis.</em></p>

<img src="Images/Screenshot3.png" alt="Screenshot 2" width="600">
<p align="center"><em>Example of the application interface displaying the visual</em></p>
