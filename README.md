# ATM Management System

## Overview
The ATM Management System is a console-based application that allows users to create bank accounts, log in, manage their accounts, and perform transactions such as deposits and withdrawals. The system ensures secure handling of user data and provides functionalities for account management.

## Features
- Create a new bank account
- Generate a new PIN for existing accounts
- User login with account ID and PIN
- Forgot PIN recovery using a security phrase
- Deposit and withdraw money
- Check account balance
- Logout functionality

## Technologies Used
- C++: The primary programming language used for developing the application.
- Standard Libraries: Utilizes standard libraries for input/output operations, file handling, and data manipulation.

## File Structure
- `main.cpp`: The main source file containing the implementation of the ATM Management System.

## How to Compile and Run
1. Ensure you have a C++ compiler installed (e.g., g++, clang++).
2. Open a terminal and navigate to the directory containing `main.cpp`.
3. Compile the program using the following command:
   ```bash
   g++ main.cpp -o atm_management_system
   ```
4. Run the compiled program:
   ```bash
   ./atm_management_system
   ```

## Usage
1. Upon running the program, you will be presented with a main menu.
2. Choose an option by entering the corresponding number.
3. Follow the prompts to create an account, log in, or perform transactions.

## Data Storage
User account information is stored in a text file named `account.txt`. Each line in the file contains the following fields separated by a pipe (`|`):
- Username
- Account ID
- PIN
- Security phrase
- Account balance

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## License
This project is open-source and available under the MIT License.

## Acknowledgments
- Thanks to the contributors and the community for their support and feedback.
