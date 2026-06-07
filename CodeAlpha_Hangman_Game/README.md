# 🎮 Hangman Game

[![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A sleek, terminal-based Hangman game developed as part of the **CodeAlpha Internship**. Challenge your vocabulary and save the hangman from his fate!

---

## ✨ Features

- 🧠 **Smart Word Selection**: Randomly picks words from a curated list.
- ❤️ **Life System**: You have 6 attempts to guess the word before the game ends.
- ⌨️ **Interactive UI**: Real-time feedback on guesses and remaining attempts.
- 🛡️ **Error Handling**: Prevents duplicate guesses from wasting your turns.

## Key Concepts Used:
 random, while loop, if-else, strings, lists.

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).

### Installation & Run
1. **Clone the repository**:
   ```bash
   git clone https://github.com/shwetapandya31/codealpha_tasks.git
   ```
2. **Navigate to the directory**:
   ```bash
   cd CodeAlpha_Hangman_Game
   ```
3. **Execute the game**:
   ```bash
   python hangman.py
   ```

## 🎮 How to Play

1. The game will display underscores `_` representing the letters of a secret word.
2. Enter one letter at a time when prompted.
3. If the letter is in the word, it will be revealed.
4. If the letter is not in the word, you lose a life.
5. Win by guessing all the letters or lose when you run out of 6 lives!

## 🛠️ Built With

- **Python**: Core logic and game loop.
- **Random Module**: For dynamic word selection.

---

