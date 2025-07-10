# OIBSIP_Java-Development_task3

https://drive.google.com/file/d/1hDl3IvWlgs80sXMc_bevuvIoBKu2p-CH/view?usp=drive_link

 💳 ATM Interface – Java Console Application

This is a console-based ATM Interface project built using Java. It simulates the basic operations of an Automated Teller Machine (ATM), such as user authentication, withdrawal, deposit, transfer, and viewing transaction history. The application is designed using object-oriented programming (OOP) principles, making it a great learning project for beginners.

 🧠 Project Objective

The main goal of this project is to develop a simple, interactive system that allows users to perform basic banking operations through a secure login system. It mimics a real ATM system in a simplified way and runs entirely through the console.

🔧 Technologies Used

- Java (JDK 8 or higher)
- Console/Terminal** for user interaction
- No external libraries or database used

 📁 File Information

- ATMSystem.java – Contains the entire source code with all five classes:
  - User
  - ATMOperations
  - ATMSystem (with the main() method)
  - Internal use of Scanner and List for data handling
 🔐 User Login (Authentication)

To start using the system, a user must provide:
- A valid User ID
- The corresponding PIN

For testing, a default user is preloaded:

- User ID: user123
- PIN: 1234
- Initial Balance: ₹10,000

✅ Features

| Feature             | Description |
|---------------------|-------------|
| User Login          | Verifies user ID and PIN before access |
| Transaction History | Displays a list of all deposits, withdrawals, and transfers |
|   Withdraw          | Withdraws a valid amount from the current balance |
| Deposit             | Adds a valid amount to the user’s balance |
|  Transfer           | Transfers amount to another user ID (simulated) |
| Exit                | Ends the session gracefully |

