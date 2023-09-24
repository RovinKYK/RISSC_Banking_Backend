# RISSC_Banking_Backend

This project is the back-end implementation using NodeJS and MySQL for a banking system designed to facilitate bank branch management, internal fund transfers, and loan processing. For the front-end, please refer to the [RISSC_Banking_Frontend](https://github.com/RovinKYK/RISSC_Banking_Frontend).

### System Features

- The bank contains a series of branches, including the head office.
- Each branch has a branch manager and a set of employees.
- Employees need access to the Core Banking System (CBS).
- Customers can open new accounts by visiting any branch.
- Accounts are affiliated with a branch, but customers can choose different branches for each account.
- Customers can be individuals or organizations (NGO, Company, etc.).
- The bank offers two types of accounts: Savings and Checking.
- Savings accounts offer high-interest rates but allow only 5 withdrawals per month.
- Interest rates and minimum required balances for Savings accounts vary based on the plan.
- Current accounts provide no interest rate but do not limit the number of withdrawals.
- Customers can start Fixed Deposits (FD) with the bank, but must have a Savings account.
- FD plans have different interest rates and durations.

## Database Design

For the database design, please refer to the [ER Diagram](https://github.com/RovinKYK/RISSC_Banking_Backend/blob/main/ER%20Diagram.pdf).

## Usage

This system provides a user interface to interact with the database features for testing and validation. The application allows users to perform the following actions:

- Add new recipients
- Send emails
- Print names of recipients with birthdays on the current date
- Print details of emails sent on a specified date
- Print the number of recipient objects in the application

## Note

- The project assumes certain domain-specific details, such as account types, interest rates, and loan rates, based on related material and assumptions.

- Dummy data is populated in the database for testing purposes. SQL queries can be used to manually input the dummy data.

- Ensure that the front-end and back-end are properly integrated for the complete functioning of the system.
