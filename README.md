# 🧮 Python Mini Project 2 – Command Line Calculator
## 📌 Project Overview

# This project is a simple command-line calculator built using:

User-defined functions

Built-in Python functions

Conditional statements (if-elif-else)

Loops (while)

Input handling

Type casting

String methods (upper(), lower())

### The calculator performs basic arithmetic operations:

➕ Addition

➖ Subtraction

✖️ Multiplication

➗ Division

## 🚀 Features

✔ Continuous calculations using a while loop
✔ Accepts multiple input formats (A, ADD, Addition, etc.)
✔ Uses reusable function blocks
✔ Clean separation of logic
✔ User-friendly prompts
✔ Exit option after each calculation

<img width="1680" height="1050" alt="Screenshot 2026-02-11 at 11 41 34 PM" src="https://github.com/user-attachments/assets/1628da13-c7f2-498d-849a-956b654bc5e8" />



## 🧠 Concepts Implemented
### 🔹 1. User-Defined Functions

Each arithmetic operation is defined as a reusable function:
```
def add(x, y):
    return x + y

def sub(x, y):
    return x - y

def multi(x, y):
    return x * y

def div(x, y):
    return x / y
```
✔ Promotes modular programming
✔ Improves readability
✔ Encourages code reusability

### 🔹 2. Input Handling
```
choice = input("Enter choice (Add, Sub, Mul, Div)")
num1 = float(input("Enter 1st number: "))
num2 = float(input("Enter 2nd number: "))
```
✔ Uses input() for user interaction
✔ Converts values using float()
✔ Handles uppercase/lowercase using .upper()

### 🔹 3. Conditional Logic
```
if choice.upper() in ('A', 'ADD', 'ADDITION'):
```
✔ Accepts multiple variations of input
✔ Improves user flexibility
✔ Demonstrates logical grouping

### 🔹 4. Loop Control
```
while True:
```
The calculator continues running until the user chooses to exit.
```
if next_calculation.lower() in ('no', 'n'):
    break
```
✔ Uses infinite loop pattern
✔ Controlled exit using break
✔ Real-world CLI behavior
```
Enter A for addition:
Enter S for subtraction:
Enter M for multiplication:
Enter D for division:

Enter choice (Add, Sub, Mul, Div): D
Enter 1st number: 8
Enter 2nd number: 2
Result:  8.0 / 2.0  =  4.0

Want to do next calculation? (yes/no): no
```
### 🛠 Skills Demonstrated

Function design

Clean modular structure

Data type conversion

Input validation

String handling methods

Loop control

Beginner CLI application design

### 🎯 Learning Outcome

**This project strengthens:**

Logical thinking

Program structure planning

Reusability of code

Real-world program flow

Control flow mastery

It builds a strong foundation for:

Data Science

Backend Development

Automation

Software Engineering

### 🏁 Conclusion

This calculator project demonstrates core Python fundamentals through a practical and interactive mini application. It reflects strong understanding of:

Functions

Loops

Conditions

Built-in methods

Clean coding practices

