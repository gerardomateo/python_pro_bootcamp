# Number Guessing Game

A command-line game written in Python where you try to guess a secret number between 1 and 100 before you run out of attempts.

## How It Works

1. The computer picks a random number between 1 and 100.
2. You choose a difficulty:
   - **Easy:** 10 attempts
   - **Hard:** 5 attempts
3. After each guess, the game tells you whether your guess was too high or too low.
4. Guess the number before your attempts run out to win.

## Example

```
Choose a difficulty. Type 'easy' or 'hard': easy
You have 10 attempts remaining to guess the number.
Make a guess: 50
Too high.
Guess again.
You have 9 attempts remaining to guess the number.
Make a guess: 25
Too low.
Guess again.
...
You got it! The answer was 37
```

## Run It

Requires Python 3.

```bash
python main.py
```

## Concepts Practiced

- Functions with parameters and return values
- Global constants
- `while` loops and conditional logic
- User input handling and type conversion
- The `random` module

## Project Structure

```
Number Guessing Project/
└── main.py
```
