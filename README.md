NUMBER GUESSING GAME IN PYTHON

DESCRIPTION:
This is a simple Python command-line game where the computer randomly selects a number between 1 and 100, 
and the user has to guess it. The program gives hints if the guess is too high or too low and counts the number of attempts.

FEATURES:
- Random number generation between 1 and 100
- User input validation (non-number entries are handled)
- Unlimited guessing attempts until the correct number is found
- Tracks and displays number of attempts

REQUIREMENTS:
- Python 
- No additional libraries required

HOW TO RUN:
1. Save the code in a file named number_guessing_game.py
2. Open your terminal or command prompt
3. Run the script with:
   python number_guessing_game.py
4. Follow the on-screen instructions to play

SAMPLE OUTPUT:
----------------------------------
Welcome to the Number Guessing Game!
I am thinking of a number between 1 and 100.
Enter your guess: 40
Too low! Try again.
Enter your guess: 60
Too high! Try again.
Enter your guess: 50
Congratulations! You guessed the number in 3 attempts.
----------------------------------

FILE STRUCTURE:
- number_guessing_game.py  →  Python source code
- README.txt               →  This documentation file

FUTURE IMPROVEMENTS:
- Add a difficulty level (Easy/Medium/Hard)
- Add a maximum number of allowed guesses
- Add high-score tracking
- Add graphical interface using Tkinter

