# Hangman Game (Python)

A simple command-line based Hangman game built using Python.  
The player guesses letters to find the hidden word before running out of lives.

## Features

- Randomly selects a word from a predefined list
- Takes user input letter by letter
- Displays word progress using underscores (_)
- Tracks remaining lives
- Shows win or lose message based on guesses

## Technologies Used

- **Python 3**
- Built-in Python modules:
  - `random`

## How It Works

1. The program selects a random word from a word list.
2. The word is hidden using underscores (_).
3. The player guesses one letter at a time.
4. If the guessed letter is correct, it is revealed in the word.
5. If the guessed letter is wrong, one life is reduced.
6. The player:
   - **Wins** if all letters are guessed correctly.
   - **Loses** if all lives are used up.

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/chinnikusuma973/Hangman-gam.git
