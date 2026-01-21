# Tutedude_Assignment_1
README – Python Input and Basic Operations

This repository contains two simple Python programs that demonstrate how to take user input and perform basic operations. These tasks are designed for beginners to understand input handling, arithmetic operations, string manipulation, and formatted output in Python.


---

Task 1: Basic operations

Description

Task 1 works as a basic operations. It takes two numbers from the user and performs four arithmetic operations:

Addition

Subtraction

Multiplication

Division


Code Explanation

num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

The program asks the user to enter two numbers.

input() takes input as a string, so float() is used to convert it into a decimal number.


print(f"Addition: {num1 + num2}")
print(f"Subtraction: {num1 - num2}")
print(f"Multiplication: {num1 * num2}")
print(f"Division: {num1 / num2}")

These lines perform arithmetic operations on the two numbers.

f"" is an f-string, which allows inserting variables directly into the output.

Each operation is calculated and printed clearly.


Example Output

Enter first number: 10
Enter second number: 5
Addition: 15.0
Subtraction: 5.0
Multiplication: 50.0
Division: 2.0

Purpose

This task helps in understanding:

User input in Python

Type conversion using float()

Basic arithmetic operators

Formatted printing



---

Task 2: Personalized Greeting

Description

Task 2 takes the user’s first name and last name, combines them, and displays a personalized greeting message.

Code Explanation

first_name = input("Enter your first name: ")
last_name = input("Enter your last name: ")

The program asks the user to enter their first and last name.

Inputs are stored as strings.


full_name = first_name + " " + last_name

Concatenates the first name and last name with a space in between to form a full name.


print(f"Hello, {full_name}! Welcome!")

Prints a greeting message using the full name.

Uses an f-string for clean and readable output.


Example Output

Enter your first name: Bro
Enter your last name: Kumar
Hello, Bro Kumar! Welcome!

Purpose

This task helps in understanding:

String input handling

String concatenation

Formatted output using f-strings



---

Requirements

Python 3.x installed on your system



---

How to Run

1. Save the code in a file, for example: main.py


2. Open a terminal or command prompt.


3. Run the program using:

python main.py


4. Follow the on-screen instructions to enter inputs.




---

Learning Outcome

By completing these tasks, you will understand:

How to take numeric and text input from users

How to perform arithmetic calculations

How to work with strings

How to display results in a user-friendly format


These two programs form a strong foundation for learning Python basics.
