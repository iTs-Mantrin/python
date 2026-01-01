# Assignment 1 – Module 2: Basic Python Concepts

This repository contains solutions for **Assignment 1** of the Python course, focusing on **basic Python concepts** such as user input, arithmetic operations, string manipulation, and output formatting.

---

## 📌 Task 1: Perform Basic Mathematical Operations

### Description
This Python program:
1. Takes **two numbers** as input from the user.
2. Performs the following mathematical operations:
   - Addition
   - Subtraction
   - Multiplication
   - Division
3. Displays the result of each operation on the screen.

### Sample Code Logic
```python
num1 = int(input("Please Enter the first number: "))
num2 = int(input("Please Enter the second number: "))

add = num1 + num2
sub = num1 - num2
mul = num1 * num2
div = num1 / num2

print("Addition:", add)
print("Subtraction:", sub)
print("Multiplication:", mul)
print("Division:", div)
```
## 📌 Task 2: Create a Personalized Greeting

### Problem Statement
Write a Python program that:
1. Takes the user's **first name** and **last name** as input.
2. Concatenates the first name and last name into a **full name**.
3. Prints a **personalized greeting message** using the full name.

---

### 🧠 Program Explanation
- The program uses the `input()` function to accept user input.
- The first name and last name are combined using string concatenation.
- A friendly greeting message is displayed using the full name.

---

### 🧪 Sample Code
```python
first_name = input("Please enter first name: ")
last_name = input("Please enter last name: ")

full_name = first_name + " " + last_name

print("Hello,", full_name + "!", "Welcome to the Python program.")
```
