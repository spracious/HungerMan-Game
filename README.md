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

   git clone https://github.com/yourusername/hangman-game.git

 
Navigate to the project directory:

cd hangman-game
Open index.html in a web browser: Simply double-click the index.html file or open it manually in your browser.

File Structure

index.html: The HTML structure of the game.
styles.css: The CSS file for styling the game interface.
script.js: The JavaScript file that contains the game logic.
Technologies Used

HTML: For structuring the webpage.

CSS: For styling the user interface.

JavaScript: For implementing the game logic and interactivity.
Future Enhancements

Mobile Responsiveness: Making the game interface fully responsive for mobile devices.

Difficulty Levels: Adding levels of difficulty with more words or reduced guesses.
Hint System: Implementing hints to assist players when they're stuck.
Multiplayer Mode: Allowing two players to take turns guessing the word.
Contributing
Contributions are welcome! If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.

License
This project is open-source and available under the MIT License.


### Instructions:

1. Replace `https://github.com/yourusername/hangman-game.git` with the actual URL of your repository.
2. Ensure that the license file is added if you want to include the MIT License.

This `README.md` provides clear instructions for users on how to set up and play the game, details about the features, and room for future enhancements.





