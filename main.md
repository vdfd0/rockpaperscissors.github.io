# Rock Paper Scissors

This is a simple Rock Paper Scissors game implemented using HTML, CSS, and JavaScript.

## HTML Structure

The HTML structure of the game consists of the following elements:

- `<h1>`: Heading displaying the game title.
- `<p>`: Paragraph displaying the instruction.
- `<button>`: Three buttons representing the player's choices (rock, paper, scissors).
- `<div>`: A div element to display the result of each round.

## CSS Styling

The CSS code includes the following styles:

- `body`: Sets the text alignment and font family.
- `h1`: Defines the color for the game title.
- `.choice-btn`: Styles the choice buttons with specific margins, padding, font size, cursor, background color, and text color.
- `#result`: Styles the result div element with margin and font size.

## JavaScript Logic

The JavaScript code handles the game logic. It includes the following functions:

- `computerPlay()`: Generates a random choice for the computer player.
- `playRound(playerSelection, computerSelection)`: Determines the winner or tie based on the player's and computer's choices.
- `displayResult(result)`: Displays the result of each round on the page.
- Event listeners are attached to the choice buttons, which call the necessary functions when clicked.

## Game Flow

1. The player selects their choice by clicking on one of the buttons (rock, paper, or scissors).
2. The computer generates a random choice.
3. The `playRound()` function compares the player's and computer's choices and determines the result.
4. The `displayResult()` function displays the result on the page.
5. If the player wins or loses, the page automatically refreshes after 0.55 seconds to start a new round.

---

This Markdown file describes the HTML, CSS, and JavaScript code for the Rock Paper Scissors game. To play the game, you need to copy and paste the HTML code into an HTML file and open it in a web browser.

Please note that if you are using Google Sites, the JavaScript code may not execute as Google Sites does not support running custom JavaScript code within pages.
