# Capstone Project: Introduction to Python Programming

Welcome to my capstone project for the **"Introduction to Python Programming"** course. This project is a demonstration of my understanding of fundamental Python concepts, including data types, control flow, functions, loops, and user interaction using `input()`.

## 📁 Project Overview

This notebook contains:
- A comprehensive Python program that:
  - Greets the user.
  - Prompts for user input.
  - Performs operations like calculating a factorial.
  - Demonstrates use of conditionals and loops.
  - Uses functions to maintain modular code.

## 🧠 Learning Objectives

- Understand and apply basic Python syntax.
- Use functions to organize code.
- Implement conditionals (`if-else`) and loops (`for`, `while`) for logic flow.
- Handle user input and output.
- Practice writing clean and reusable code.

## 🛠️ Technologies Used

- Language: Python 3
- Platform: Jupyter Notebook

## 📷 Preview

Here's a sample from the notebook:

```python
def factorial(n):
    if n == 0 or n == 1:
        return 1
    else:
        return n * factorial(n-1)

number = int(input("Enter a number: "))
print("Factorial is:", factorial(number))
