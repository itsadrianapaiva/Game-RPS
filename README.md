# **Rock, Paper, Scissors Game Documentation**

## **Table of Contents**
1. [Introduction](#introduction)
2. [Features](#features)
3. [Code Structure](#code-structure)
4. [Functions Explanation](#functions-explanation)
5. [Possible Improvements](#possible-improvements)
6. [Credits](#credits)

## **Introduction**

The Rock, Paper, Scissors game is a simple web-based implementation of the classic hand game. This project was built using HTML, CSS, and JavaScript. The objective is to allow the player to compete against the computer by selecting one of the three options: Rock, Paper, or Scissors. The computer randomly chooses an option, and the winner is determined based on the rules of the game.

## **Features**

- User-friendly interface.
- Real-time score tracking.
- Game resets when a player or the computer wins 3 rounds.
- Responsive design for different screen sizes.
- Option to reset the game at any time.

## **Code Structure**

- `index.html`: Contains the basic structure of the webpage, including buttons for Rock, Paper, Scissors, and display elements for the scores and results.
- `styles.css`: Contains the styling rules for the game, ensuring a visually appealing layout.
- `script.js`: Contains the game logic, handling user input, random computer selection, score tracking, and determining the winner.

## **Functions Explanation**

### `getRandomComputerResult()`
- **Purpose**: Randomly selects Rock, Paper, or Scissors for the computer.
- **Return**: A string (`"Rock"`, `"Paper"`, or `"Scissors"`).

### `hasPlayerWonTheRound(player, computer)`
- **Parameters**:
  - `player` (string): The player's choice.
  - `computer` (string): The computer's choice.
- **Return**: Boolean (`true` if the player wins, `false` otherwise).

### `getRoundResults(userOption)`
- **Purpose**: Determines the outcome of a round, updates scores, and returns a message indicating the result.
- **Parameters**: `userOption` (string): The player's choice.
- **Return**: A string indicating the result of the round.

### `showResults(userOption)`
- **Purpose**: Updates the UI to display the result of the round, the current scores, and checks if a player has won the game.
- **Parameters**: `userOption` (string): The player's choice.

### `resetGame()`
- **Purpose**: Resets the game, scores, and UI elements to their initial state.

## **CSS Styling**

The game uses basic CSS to style the elements:
- **Flexbox**: Used for layout and alignment.
- **Colors and Fonts**: Simple color scheme and fonts for readability.`

## **Possible Improvements**

- **Add Animations**: Improve user experience by adding animations when selecting options or displaying results.
- **Add Sound Effects**: Provide audio feedback for player actions.
- **Expand to Multiplayer**: Allow two players to play against each other.
- **Difficulty Levels**: Introduce different difficulty levels for the computer.

## **Credits**

- **Developer**: Adriana Paiva
- **Resources**: freeCodeCamp and Youtube videos
