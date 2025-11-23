# PROJECT_VITYARTHI
>#Overview

This project is a simple command-line number guessing game written in Python. The program randomly selects a secret number within a defined range, and the player has four attempts to guess it correctly. After each guess, the game provides feedback whether the guess is too high, too low, or correct. The game ends when the player guesses correctly or runs out of attempts.

>#Features

User friendly interface that greets the player by name.
Generates a random secret number within a specified range (default 1 to 10).
Limits the player to 4 guesses per game.
Provides hints after each incorrect guess (“Too high” or “Too low”).
Validates guesses to ensure they fall within the allowed range.
Informs the player when guesses run out and reveals the secret number.
Handles invalid inputs gracefully.

>#Technologies/Tools Used

Python 3 (standard library)
'random module' for secret number generation
Command-line interface for interaction with the player

>#Installation & Running the Project

Ensure Python 3 is installed on your machine. You can download it from https://python.org.
Save the game script as a .py file, for example, guessing_game.py.
Open a terminal or command prompt.
Navigate to the folder containing the script.
Run the game using the command: python guessing_game.py

>#Testing Instructions

Run the script multiple times to ensure the random number changes each game.
Test guesses inside and outside the valid number range to verify validation.
Input both valid numerical guesses and invalid inputs (e.g., letters or special characters) to check error handling.
Confirm the game ends after 4 incorrect guesses and properly acknowledges a correct guess at any point.

>#Screenshots:
Here are some screenshot of the game:

When the guess is right. 

<img width="668" height="334" alt="image" src="https://github.com/user-attachments/assets/325d4246-03cb-4cce-b6e1-4db97711a0f5" />


When u couldn't make the right guess.

<img width="694" height="472" alt="image" src="https://github.com/user-attachments/assets/7d19ebef-0288-4702-9a1e-4463766000cf" />





