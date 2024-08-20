# ATM-Application
**Overview**
This project is a simple ATM system implemented in Python, simulating basic ATM functionalities such as account creation, authentication, deposits, withdrawals, balance checking, and password management. The system supports both user and admin accounts, with specific privileges and restrictions.

**Features**

**User Features:**

Account Creation: Admin can create accounts for users with an initial balance.

Authentication: Users can log in with their user ID and password.

Deposit: Users can deposit a specified amount using defined denominations.

Withdraw: Users can withdraw a specified amount using defined denominations.

Check Balance: Users can view their current account balance.

Change Password: Users can change their account password.

**Admin Features:**

Admin Authentication: Admin can log in with the admin password.

View All Users: Admin can view a list of all user accounts, including their balances and lock status.

Warning Message: The system displays a warning if the total balance across all accounts is less than ₹75,000.

**Security Features:**

Account Locking: Accounts are locked after three unsuccessful login attempts.

Admin Locking: The admin account is locked after three unsuccessful login attempts.

# Getting Started

**Prerequisites**

Python 3.x

**Installation**
      1. Clone the repository:
      
            git clone https://github.com/yourusername/ATM-System.git
            
      2. Navigate to the project directory:
      
            cd ATM-System
            
**Usage**

**Run the script:**

python atm_system.py

**User Guide**

**Main Menu:**

1. User Login: Allows users to log in and perform transactions.
2. Admin Login: Allows admin to log in and manage user accounts.
3. Exit: Exits the program.
   
**User Interface:**

1. Deposit: Enter the amount and the number of bills for each denomination to deposit money.
2. Withdraw: Enter the amount and the number of bills for each denomination to withdraw money.
3. Check Balance: View the current balance of your account.
4. Change Password: Change your account password by providing the current and new passwords.
5. Exit: Log out from the user interface.
   
**Admin Interface:**

1. View All User Accounts: Displays a list of all user accounts, their balances, and whether they are locked.
2. Exit Admin Interface: Log out from the admin interface.
   
**Acknowledgments**
This project is inspired by basic ATM systems and is designed for educational purposes to practice Python programming.
