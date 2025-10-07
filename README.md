Database Management System (DBMS)
📌 Project Overview

This project is a command-line Database Management System (DBMS) built entirely using Bash scripting.
It simulates the core functionalities of a traditional database system — allowing users to create, connect, and manage databases and tables through a simple terminal interface.

The system emphasizes input validation, error handling, and data consistency, ensuring a realistic and reliable user experience.

⚙️ Tools & Technologies

Bash Shell Scripting (Linux environment)

File System-based Data Storage

Command-Line Interface (CLI)

Repository Structure
1️⃣ scripts/

Contains all Bash scripts that implement the DBMS logic:

main_menu.sh — The entry point of the program; displays the main options and validates user input.

create_database.sh — Handles database creation after performing name and format validations.

display_databases.sh — Lists all available databases in the system.

connect_database.sh — Allows the user to connect to an existing database and perform table operations (create, insert, view, etc.).

Each script includes extensive validation checks to ensure data integrity and prevent invalid operations.

2️⃣ documentation/

Includes:

A checklist document describing all implemented validations and features.

A demo video showing the system in action — including database creation, table operations, and error handling demonstrations.

🧩 Main Features & Validations
🏠 Main Menu

Validates that user input is a number within the available options.

Rejects invalid characters such as backslashes (\).

Displays clear error messages for invalid inputs.

🗄️ Create Database

Replaces spaces in names with underscores.

Prevents use of special characters or starting a name with a number.

Checks if a database with the same name already exists.

Creates a dedicated folder for each new database if all validations pass.

📋 Display Databases

Displays all existing databases in the directory.

Alerts the user if no databases exist.

🔗 Connect to Database

Allows navigation into an existing database and provides table operations:

a) Table Creation

Validates the table name format and uniqueness.

Ensures the name contains no spaces, special characters, or invalid input.

Creates a new table file if checks pass.

b) Insert Into Table

Validates table existence and structure.

Ensures the Primary Key (PK) is not empty and unique.

Checks data type validity before insertion.

Replaces spaces with underscores and rejects special characters.

🧠 Key Functional Concepts

Database-as-Directory: Each database is represented as a folder.

Table-as-File: Each table is stored as a separate file inside its parent database.

Data Integrity: Enforced through strict validation and input control.

Error Handling: The system provides clear and user-friendly feedback messages.

📺 Demo & Documentation

You can find:

A detailed feature checklist explaining all implemented functionalities.

A demo video showing practical usage of the DBMS from the terminal.

🎯 Project Purpose

This project demonstrates:

Proficiency in Bash scripting and automation.

Strong understanding of database structures and logic flow.

Ability to design modular scripts and manage file-based data systems.

Focus on data validation, user experience, and error prevention.

Author

Fatma Hamed Ibrahim Morsi
Data Engineer | Bash & Linux Enthusiast
Passionate about backend automation, scripting, and database systems.
