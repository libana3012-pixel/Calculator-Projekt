# Number Guessing Game

## Overview

This project is a simple command-line number guessing game written in Python.
The program generates a random number between 1 and 100, and the user must guess the correct number. After each guess, the program provides feedback indicating whether the guess was too high or too low.

The game continues until the user correctly guesses the secret number.

---

## Features

* Random number generation
* Interactive user input
* Feedback after each guess
* Counts the number of attempts taken to find the correct answer

---

## How the Game Works

1. The program starts by generating a random number between **1 and 100** using Python’s `random` module.
2. The user is prompted to enter a guess.
3. The program compares the guessed number with the secret number.
4. If the guess is lower than the secret number, the program displays **"Too low. Try again."**
5. If the guess is higher than the secret number, the program displays **"Too high. Try again."**
6. The process repeats until the correct number is guessed.
7. Once the user guesses the correct number, the program displays a success message and the total number of attempts.

---

## Example

Example interaction in the terminal:

```text
Number Guessing Game
Guess a number between 1 and 100: 50
Too low. Try again.
Guess a number between 1 and 100: 75
Too high. Try again.
Guess a number between 1 and 100: 63
Correct! You guessed it in 3 attempts.
```

---

## Technologies Used

* Python 3
* Standard Python Library (`random` module)

---

## How to Run the Program

1. Make sure Pyt
