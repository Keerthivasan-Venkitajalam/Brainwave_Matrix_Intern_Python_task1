# ATM Interface

## Overview

This project is a Python-based ATM interface that simulates the basic functionalities of an Automated Teller Machine (ATM). The program allows users to deposit money, withdraw funds, transfer money, check their balance, and view their transaction history. The code ensures secure user authentication and provides a realistic experience for managing financial transactions.

## Features

- **User Authentication**: Users can log in using a user ID and PIN.
- **Deposit Funds**: Users can add money to their account.
- **Withdraw Funds**: Users can withdraw money from their account.
- **Transfer Funds**: Users can transfer money to other accounts, phone numbers, or card numbers.
- **Balance Inquiry**: Users can check their current balance.
- **Transaction History**: Users can view their past transactions.
- **Secure Transactions**: Ensures transactions are secure with a passcode.

## Getting Started

### Prerequisites

- Python 3.x installed on your machine.
- Install the required module by running:
  ```bash
  pip install tabulate
  ```

### Running the Program

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/your-username/atm-interface.git
    ```

2. Navigate to the project directory:
    ```bash
    cd atm-interface
    ```

3. Run the `atm_interface.py` file:
    ```bash
    python atm_interface.py
    ```

### Usage

- Upon running the program, you will be prompted to enter a User ID and PIN.
- After successful login, you can choose from various operations such as deposit, withdraw, transfer, balance inquiry, and viewing transaction history.
- Follow the on-screen prompts to complete each transaction.
- The program will display relevant messages for each operation and update the transaction history accordingly.

## Code Structure

- **`ATM` Class**: Contains methods for deposit, withdraw, transfer, balance inquiry, and transaction history.
- **`display_logo` Function**: Displays an ASCII art logo for the ATM interface.
- **`atm_interface` Function**: Handles user interactions and provides a menu-driven interface for ATM operations.

## Example

```bash
$ python atm_interface.py
Welcome to the ATM Interface
Enter User ID: 123456
Enter PIN: 654321
Login successful!

ATM Operations:
1. Deposit
2. Withdraw
3. Transfer
4. Check Balance
5. Transaction History
6. Quit
Enter your choice (1/2/3/4/5/6): 1
Enter the deposit amount: $500
Enter 4 or 6 digit pass_code: 1234
Deposited $500. New balance: $100500
```

## Contributing

If you'd like to contribute to this project, please fork the repository and use a feature branch. Pull requests are warmly welcome.

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-branch-name`.
5. Submit a pull request.

## Acknowledgments

- ASCII art generated using [ASCII Art Archive](https://www.asciiart.eu/).


