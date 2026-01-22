# Budget Tracker (Java Console Application)

## Overview
Budget Tracker is a simple Java console-based application that helps users manage their income and expenses. It allows users to add income, record expenses, and view their current balance through a menu-driven interface.

This project is suitable for beginners learning core Java concepts such as classes, methods, loops, conditionals, and user input handling.

---

## Features
- Add income to the budget
- Add expenses and subtract them from the balance
- View current balance at any time
- Menu-driven console interface
- Continuous execution until exit is selected

---

## Technologies Used
- Java
- Scanner (for user input)
- Console-based interface

---

## Project Structure

---

## ▶️ How to Run the Application

### Prerequisites
- Java JDK 8 or higher installed

### Steps
1. Compile the Java file:
   ```bash
   javac BudgetTracker.java

### ▶️ Run the Program
```bash
java BudgetTracker

## ⚙️ How the Application Works
- The application starts with a balance of `0.0`
- Users choose from a menu:
  - Add Income
  - Add Expense
  - View Balance
  - Exit
- Income increases the balance
- Expenses decrease the balance
- The program continues until the user exits

## Sample Output:
1. Add Income
2. Add Expense
3. View Balance
4. Exit
Enter your choice: 1
Enter income amount: 3000

1. Add Income
2. Add Expense
3. View Balance
4. Exit
Enter your choice: 3
Current Balance: Rs3000.0

## ⚠️ Limitations
- No data persistence (data resets on program restart)
- No validation for negative inputs
- Console-based application only
