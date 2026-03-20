# 🎮 Hangman Game Challenge

## 🎯 Objective
Build a console Hangman game in Python that reads a random word, accepts letter guesses, shows progress, and ends with win/lose.

## 📝 Tasks

### 🛠️ Core gameplay
#### Description
Implement the main Hangman loop:
- choose a random word from a list
- prompt user for letter input
- update and show guessed letters in `_ _ _` format
- track incorrect attempts
- avoid duplicate error counts for repeated letters

#### Requirements
Completed program should:
- use `random.choice(...)`
- show current guessed state
- decrement remaining attempts on wrong guesses
- keep guessed letters list

### 🛠️ Win/Lose and restart
#### Description
Add end-game logic and optional replay support.

#### Requirements
Completed program should:
- detect full word completion (win)
- detect attempt exhaustion (lose)
- print final message and reveal word
- optionally ask “Play again? (y/n)”
