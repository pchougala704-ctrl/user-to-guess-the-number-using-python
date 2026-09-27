# Number Guessing Game (Python)

A simple command-line game where the computer picks a random number between 1 and 100, and you try to guess it.

## How It Works

1. The program generates a random number between 1 and 100.
2. You're prompted to enter a guess.
3. After each incorrect guess, the program tells you if your guess was **too high** or **too low**.
4. The game ends when you guess correctly, and the total number of attempts is displayed.

## Requirements

- Python 3.x

## Running the Game

```bash
python guess_the_number.py
```

## Example

```
Welcome to the Number Guessing Game!
I'm thinking of a number between 1 and 100.
----------------------------------------
Enter your guess: 50
Too low! Try again.
Enter your guess: 75
Too high! Try again.
Enter your guess: 63
Too low! Try again.
Enter your guess: 70

Congratulations! You guessed it in 4 attempts!
```
