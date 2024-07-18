The code provided creates a simple web-based game called "Guess My Number!". Here’s how it works:

**Overview:**

**Objective:** The player has to guess a randomly generated number between 1 and 20.
**Interface:** The webpage consists of a header with the game title, a button to restart the game, and a hidden number display. The main section includes an input field for the player's guess, a button to submit the guess, and messages displaying the current score, high score, and feedback.


**Functionality:**

**Starting the Game:**

When the page loads, a secret number between 1 and 20 is generated.
The player starts with a score of 20.

**Making a Guess:**

The player enters a number in the input field and clicks the "Check!" button.
If no number is entered, a message prompts the player to enter a guess.
If the guess is correct, a congratulatory message is displayed, the background changes color, and the secret number is shown.
If the guess is incorrect, the player is informed whether the guess was too high or too low, and the score decreases by one point.
The game continues until the player guesses correctly or the score reaches zero.

**High Score:**

If the player guesses the number correctly and their score is higher than the current high score, the high score is updated.

**Restarting the Game:**

Clicking the "Again!" button resets the game. A new secret number is generated, the score is reset to 20, and the game interface returns to its initial state.

**Visuals and Styling:**
The webpage has a retro game design with specific fonts and colors.
The header and main sections are styled for visual clarity and engagement.
Feedback messages and the game’s overall appearance change based on the player's actions to enhance the user experience.


In summary, the code creates an interactive and visually appealing guessing game where players try to guess a randomly generated number, receiving feedback and tracking their scores along the way.
