# Hangman Game 🎮

A fun command-line Hangman Game built using Python. The player must guess the hidden word one letter at a time before running out of lives. The game includes visual hangman stages and interactive gameplay.

---

## Features

* Random word selection
* Life tracking system
* ASCII art hangman stages
* Repeated guess detection
* Interactive command-line gameplay
* Win/Lose conditions

---

## Technologies Used

* Python 3
* Random Module

---

## Game Rules

1. The system selects a random word.
2. The player guesses one letter at a time.
3. Correct guesses reveal letters in the word.
4. Wrong guesses reduce lives.
5. The player loses when all lives are gone.
6. The player wins by guessing the complete word.

---

## How to Run the Project

### Step 1: Clone the Repository

```bash id="2n9x7m"
git clone <your-github-repo-link>
```

### Step 2: Navigate to the Project Folder

```bash id="6k3v1p"
cd hangman-game
```

### Step 3: Run the Python File

```bash id="8m4t2q"
python main.py
```

---

## Project Structure

```bash id="1v7x5r"
hangman-game/
│
├── main.py
└── README.md
```

---

## Sample Gameplay

```bash id="4p8n2z"
Guess a letter: a

_ a _ _ _

  +---+
  |   |
  O   |
 /|   |
      |
      |
=========
```

---

## Learning Outcomes

This project helps in understanding:

* Python loops and conditionals
* String manipulation
* Lists and indexing
* Random module usage
* Game logic implementation
* User input handling

---

## Future Improvements

* Add larger word database
* Add difficulty levels
* GUI version using Tkinter or Pygame
* Add score tracking
* Add multiplayer mode

---

## Author

Developed by [Charan S]
