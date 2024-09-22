# Hangman Game

This is a simple implementation of the classic **Hangman** word-guessing game built using HTML, CSS, and JavaScript. The objective of the game is to guess the hidden word by suggesting letters within a limited number of guesses.

## Features

- **Random Word Selection**: A word is randomly selected from a predefined list.
- **Word Display**: The hidden word is shown as underscores, with correctly guessed letters revealed.
- **Guess Tracking**: Incorrect guesses are tracked and displayed.
- **Win/Lose Notification**: The game notifies the player if they win or lose.
- **Restart Option**: The player can restart the game without reloading the page.
- **Simple and Clean UI**: Easy-to-use interface for a smooth game experience.

## How to Play

1. When the game starts, a word is randomly selected and hidden. It is displayed as underscores (`_`), with one underscore per letter.
2. The player can input a letter and submit it by clicking the "Guess" button or pressing "Enter".
3. If the guessed letter is in the word, it will be revealed in its correct position(s).
4. If the letter is incorrect, it is added to the list of incorrect guesses, and the number of remaining guesses decreases.
5. The game continues until:
   - The player correctly guesses all the letters in the word (Win), or
   - The player uses up all incorrect guesses (Lose).
6. After the game ends, the player can click "Restart Game" to play again with a new word.

## Getting Started

To run the game on your local machine:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/hangman-game.git

 
