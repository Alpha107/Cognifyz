# Level 2 Tasks - Python Development Internship  

This repository contains solutions for the **Level 2 tasks** assigned during the Python Development Internship at Cognifyz Technologies. Each task is implemented in Python and includes a description of the task, code implementation, and sample usage.

---

## Table of Contents  
- [Task 1: Guessing Game](#task-1-guessing-game)  
- [Task 2: Number Guesser](#task-2-number-guesser)  
- [Task 3: Password Strength Checker](#task-3-password-strength-checker)  
- [Task 4: Fibonacci Sequence](#task-4-fibonacci-sequence)  
- [Task 5: File Manipulation](#task-5-file-manipulation)  

---

## Task 1: Guessing Game  

### Task Description  
Write a Python program that generates a random number between 1 and 100. The user should guess the number, and the program provides hints ("too high" or "too low") until the correct number is guessed.

### Implementation  
```python
import random

def guessing_game():
    number = random.randint(1, 100)
    print("Guess a number between 1 and 100.")
    while True:
        guess = int(input("Your guess: "))
        if guess < number:
            print("Too low!")
        elif guess > number:
            print("Too high!")
        else:
            print("Congratulations! You guessed it.")
            break

guessing_game()
