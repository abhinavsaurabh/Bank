
# Bank Management System

This project is a console-based Bank Management System developed in C++.
It was created by Abhinav Saurabh during his 12th grade, demonstrating an early aptitude for software development and a keen interest in financial systems.

## Features

- **Account Creation**: Allows users to create new bank accounts with unique account numbers, account holder names, account types (Current/Savings), and initial deposits.
- **Deposit and Withdrawal**: Enables depositing and withdrawing funds from existing accounts, with validations to ensure minimum balance requirements are met.
- **Balance Enquiry**: Provides the current balance and account details for a given account number.
- **Account Modification**: Permits updating account holder information and account type.
- **Account Closure**: Facilitates the deletion of existing accounts from the system.
- **Display All Accounts**: Lists all account holders with their respective details in a tabular format.

## Code Structure

The project comprises a single C++ source file: `Bank.CPP`. The primary components include:

- **Class Definition**: The `acc` class encapsulates account-related data and functionalities. It includes member variables for account number (`ano`), account holder name (`name`), deposit amount (`dep`), and account type (`type`). Member functions manage account creation, display, modification, deposits, withdrawals, and reporting.

- **Main Function**: The `main()` function presents a user-interactive menu to perform various banking operations. It utilizes functions like `write_acc()`, `display_sp(int)`, `modify_acc(int)`, `delete_acc(int)`, `display_all()`, and `dep_withdraw(int, int)` to handle respective tasks.

- **File Handling**: Account information is stored in a binary file named `info.dat`. The system employs file streams to read from and write to this file, ensuring data persistence across sessions.

- **Utility Functions**: Additional functions manage specific operations:
  - `write_acc()`: Creates and writes a new account to the file.
  - `display_sp(int)`: Displays details of a specific account based on account number.
  - `modify_acc(int)`: Modifies details of an existing account.
  - `delete_acc(int)`: Deletes an account from the file.
  - `display_all()`: Displays all account holders' information.
  - `dep_withdraw(int, int)`: Manages deposit and withdrawal transactions.

- **Introductory Screen**: The `intro()` function displays a welcome message and project information when the program starts.

## Demonstrated Skills

Developing this project in the 12th grade showcases several competencies:

- **Programming Proficiency**: A solid understanding of C++ programming, including classes, file handling, and standard I/O operations.
- **Problem-Solving**: Ability to design and implement a functional banking system, addressing real-world requirements such as data persistence and user interaction.
- **Early Initiative**: Demonstrates a proactive approach to learning and applying programming skills to complex projects at a young age.

## Getting Started

To run the Bank Management System:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/abhinavsaurabh/Bank.git
   ```
2. **Compile the Source Code**:
   Use a C++ compiler to compile `Bank.CPP`. For example, with `g++`:
   ```bash
   g++ Bank.CPP -o BankManagementSystem
   ```
3. **Run the Executable**:
   ```bash
   ./BankManagementSystem
   ```

## Acknowledgments

This project reflects the foundational steps taken by Abhinav Saurabh in the field of software development, laying the groundwork for future endeavors in computer science.

For more projects and contributions, visit Abhinav's GitHub profile: ([github.com](https://github.com/abhinavsaurabh))
