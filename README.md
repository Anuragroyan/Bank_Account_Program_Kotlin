🏦 Banking Terminal App

Banking Terminal App is a Kotlin-based terminal application designed to demonstrate fundamental real-world banking operations through a command-line interface. It allows users to manage accounts and perform essential transactions such as deposits, withdrawals, balance checking, and account management.

🎯 Why This Project?

Banking Terminal App was built to practice Kotlin fundamentals, object-oriented programming, user input handling, conditional logic, and transaction-based application flow through a simple command-line banking system.

The project focuses on implementing real-world banking concepts while keeping the application lightweight and easy to understand.

🚀 Features

* 👤 Account creation and management
* 💰 Deposit money
* 💸 Withdraw money
* 💳 Check account balance
* 🔄 Perform banking transactions
* 🧾 Display transaction information
* 🔐 Basic account validation
* ⚠️ Handle invalid inputs and transactions
* 🖥️ Command-line interface
* 🧮 Balance calculation and management

🔄 Application Workflow

Start Application → Create / Access Account → Select Banking Operation → Deposit / Withdraw / Check Balance → Validate Transaction → Update Account → Display Result → Continue / Exit

🧩 Main Modules

👤 Account Management

Users can create and manage their basic banking account information.

Create Account → Enter Account Details → Validate Information → Access Account

💰 Deposit

Users can add money to their account.

Select Deposit → Enter Amount → Validate Amount → Add To Balance → Display Updated Balance

💸 Withdrawal

Users can withdraw money from their available balance.

Select Withdrawal → Enter Amount → Check Balance → Validate Transaction → Deduct Amount → Display Updated Balance

💳 Balance Checking

Users can view their current account balance.

Select Balance → Retrieve Account Data → Display Current Balance

🖥️ Terminal Interface

The application provides a menu-driven command-line interface where users select operations using terminal input.

🏗️ Architecture

Main Program → Banking Menu → User Input → Banking Operations → Account Data → Updated Balance → Terminal Output

Core Components

* Kotlin — Primary programming language
* Main Program — Application entry point
* Banking Menu — Handles available operations
* Account Model — Represents account information
* Transaction Logic — Processes deposits and withdrawals
* Input Handling — Reads and validates user input

🛠️ Tech Stack

Kotlin • Kotlin/JVM • Object-Oriented Programming • Collections • Control Flow • Functions • Command-Line Interface

📂 Project Structure

BankingTerminal/ → src/ → main/kotlin/ → Main.kt • Account.kt • BankingService.kt • Transaction.kt • utils/ → build.gradle.kts → settings.gradle.kts → README.md

⚙️ Getting Started

1. Clone the Repository

git clone <repository-url>
cd BankingTerminal

2. Build the Project

./gradlew build

3. Run the Application

./gradlew run

Or run the main() function directly from IntelliJ IDEA / Android Studio.

🔄 Transaction Flow

User Selects Operation → Enter Amount → Validate Input → Process Transaction → Update Balance → Display Result

🔒 Validation & Error Handling

The application can handle common banking scenarios such as:

* Invalid account information
* Invalid transaction amounts
* Withdrawal exceeding available balance
* Invalid menu selections
* Incorrect user input
* Zero or negative transaction amounts

🌍 Real-World Use Case

Banking Terminal App demonstrates the basic workflow behind a banking system and can be used as a learning project for understanding:

* 🏦 Banking operations
* 💰 Financial transactions
* 👤 Account management
* 🧮 Balance calculations
* 🖥️ Menu-driven applications


# ScreenShots  

![Screenshot 2024-04-17 224315](https://github.com/Anuragroyan/BankAccountProgram/assets/38952781/96ba0445-955f-4deb-831c-a771a5b5f484)
