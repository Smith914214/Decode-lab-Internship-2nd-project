# Expense Tracker

## Project Overview

Expense Tracker is a simple Python application that helps users record their expenses and calculate the total amount spent. This project demonstrates the use of variables, loops, user input, and accumulator logic in Python.

## Features

* Add multiple expenses
* Calculate total spending automatically
* Easy-to-use command-line interface
* Beginner-friendly Python project

## 💻 Code

```python
total = 0

n = int(input("Enter number of expenses: "))

for i in range(n):
    expense = float(input(f"Enter expense {i+1}: "))
    total = total + expense

print("\nTotal Spent =", total)

## 📋 Example Output

```
Enter number of expenses: 3
Enter expense 1: 100
Enter expense 2: 50
Enter expense 3: 20

Total Spent = 170.0
```

## 🎯 Learning Outcomes

* Working with variables
* Taking user input
* Using loops in Python
* Applying arithmetic operations
* Understanding accumulator patterns

## 👨‍💻 Author

Developed as part of Python Programming practice to strengthen programming fundamentals and data-processing concepts.
