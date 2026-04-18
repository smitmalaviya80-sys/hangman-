# Hangman Game in C++

A classic **Hangman** word-guessing game developed in C++ with a nice console-based ASCII art interface.

## 🎮 Game Overview

**Hangman** is a fun and challenging word guessing game where the player tries to guess a hidden word letter by letter.  
Every wrong guess brings the hangman one step closer to being "hanged".  
You have **9 wrong attempts** before the game ends.

### Features

- ✅ Random word selection from a word list (`word.txt`)
- ✅ Beautiful ASCII art Hangman drawing that updates with every wrong guess
- ✅ Clean bordered console interface
- ✅ Shows available letters (A–Z)
- ✅ Displays current progress of the word (e.g., `A _ E X _ S`)
- ✅ Tracks wrong guesses and remaining attempts
- ✅ Win/Lose message at the end
- ✅ Simple and beginner-friendly code structure

### How to Play

1. The game loads a random secret word from `word.txt`
2. You have to guess the word by entering one letter at a time
3. Correct letters will appear in their positions
4. Wrong letters will add a body part to the hangman
5. You win if you guess the complete word before the hangman is fully drawn
6. You lose if you make too many wrong guesses

### Controls

- Type a single letter and press Enter to guess
- Letters are case-insensitive (though currently handled in uppercase)

---

## 🛠️ How to Run

### Requirements
- Any C++ compiler (g++, Code::Blocks, Visual Studio, etc.)
- A text file named **`word.txt`** containing one word per line

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hangman-cpp.git
