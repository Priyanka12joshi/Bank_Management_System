# Bank_Management_System
Bank SThis is a simple Bank System Management Application written in Python. The program allows users to create and manage bank accounts securely, perform login operations, and view account details. It’s an excellent project for beginners to understand file handling, authentication mechanisms, and menu-driven programming in Python.
## Features ✨
Account Creation:

Users can create new bank accounts with an account number, name, account type, initial deposit, and a password.
Ensures a minimum initial deposit of ₹500 for creating new accounts.
Secure Login:

Users can log in using their account number and password for secure access to account details.
Account Details Display:

Logged-in users can view their account details like account type, balance, and personal information.
Admin Access:

Admin or general users can view a list of all registered accounts.
File Handling:

All account information is securely stored in a text file (accounts.txt) located on the desktop, ensuring data persistence.
User-Friendly Menu:

A simple, intuitive menu-driven interface for smooth navigation.
## How to Use 🚀
Prerequisites:
Install Python 3.x on your system.
Steps:
Clone the Repository:

bash
Copy code
git clone https://github.com/Priyanka12joshi/Bank_Management_System.git
cd bank-system
Run the Script:

Execute the Python script:
bash
python bank_system.py
Follow the Menu:

Create an account, log in, and explore the functionalities!

## File Structure 📁
bank_system.py: Main Python script containing all the functionality.
accounts.txt: Text file where account details are stored. This file is automatically created on the user's desktop when the script runs.

## How It Works ⚙️
Account Creation:

Users input their account details which are stored securely in a text file.
The system checks for the minimum deposit limit of ₹500.
Login System:

The login system validates the user credentials against stored account data for secure access.
Display Account Details:

Upon login, users can view their account details (like balance, account type, and name).
Admin View:

View all registered accounts in a formatted list.

## Example Usage 📖
1. Create a New Account-
Enter the Account Number: 12345
Enter the name of user: Priyanka Joshi
Enter the account type (c for current / s for savings): s
Enter the initial amount (>=500 for new account):700
Set your account password: password123

Account created successfully!
2. Login and View Account Details-
Enter your Account Number: 12345
Enter your password: password123

Welcome, Priyanka Joshi!
Account Details:
Account Number: 12345
Name: Priyanka Joshi
Account Type: Savings
Deposit: 1000
3. View All Accounts-
--- All Accounts ---
Account Number: 12345, Name: Priyanka Joshi, Type: Savings, Deposit: 1000
Account Number: 67890, Name: Ramesh Kumar, Type: Current, Deposit: 1500

## Future Improvements 🚀
Implement account transactions (deposit, withdraw, and transfer).
Add password encryption for enhanced security.
Create a graphical user interface (GUI) using Tkinter or PyQt.
Integrate a database like SQLite or MySQL for better scalability.
Introduce multi-user support with role-based access (e.g., user and admin).
Contribution 🤝
Contributions are welcome! Feel free to:

Fork this repository.
Add new features or fix bugs.
Submit a pull request to share your improvements!

## License 📜
This project is licensed under the MIT License. You are free to use, modify, and distribute the code as you see fit.

## Acknowledgments 🙌
This project is a great start for anyone interested in Python programming, especially in file handling and user authentication systems. Enjoy building and expanding it! 😊
