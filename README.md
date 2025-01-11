# Level 1 Tasks

This repository contains solutions for the **Level 1 tasks** assigned during the Python Development Internship at Cognifyz Technologies. Each task is implemented in Python and includes a description of the task, code implementation, and sample usage.

---

## Table of Contents  
- [String Reversal](#string-reversal)  
- [Temperature Conversion](#temperature-conversion)  
- [Email Validator](#email-validator)  
- [Calculator Program](#calculator-program)  
- [Palindrome Checker](#palindrome-checker)  

---

### Task 1: String Reversal  

#### Task Description  
Write a Python function that takes a string as input and returns its reverse.  
For example:  
Input: `"hello"`  
Output: `"olleh"`

#### How It Works
- The [::-1] slicing technique is used to reverse the input string.
- The function returns the reversed string.

---

### Task 2: Temperature Conversion

#### Task Description
Write a Python program to convert temperatures between Celsius and Fahrenheit.

- If the input is in Celsius, convert it to Fahrenheit.
- If the input is in Fahrenheit, convert it to Celsius.
- Validate the unit entered by the user.

#### How It Works
- Celsius to Fahrenheit: 𝐹=(𝐶×95)\+32

F=(C×59)+32

- Fahrenheit to Celsius: 𝐶=(𝐹−32)×59

C=(F−32)×95
 
The program validates the unit and displays the converted value with precision.

---

### Task 3: Email Validator

#### Task Description
Develop a Python function that validates whether a given string is a valid email address. The email address must include:

- A local part (e.g., user).
- An @ symbol.
- A domain part (e.g., example.com).

#### How It Works
- A regular expression validates the email format.
- The function returns True for valid emails and False otherwise.

---

### Task 4: Calculator Program

#### Task Description
Create a Python program that performs basic arithmetic operations based on user input:

- Addition (+), Subtraction (-), Multiplication (*), Division (/), and Modulus (%).
- Handle division by zero gracefully.

#### How It Works
- Accepts two numbers and an operator as input.
- Performs the operation and handles invalid operators and division by zero errors.

---

### Task 5: Palindrome Checker

#### Task Description
Write a Python function to check if a given string is a palindrome.

- A palindrome reads the same forward and backward (e.g., madam, racecar).
- Ignore spaces, punctuation, and letter casing.

#### How It Works
- The string is cleaned to remove spaces and non-alphanumeric characters.
- The cleaned string is checked against its reverse.

---

License
This project is licensed under the MIT License.
