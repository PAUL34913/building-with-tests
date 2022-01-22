# building-with-tests

**Simple JavaScript project built using JEST and test driven development.**

HTML and CSS for the project are pre-supplied in order to focus on the JavaScript and testing.

## Javascript Structure

- game{object}              (stores game state)
- newGame(function)     -   (resets everything and starts new turn)
- addTurn(function)     -   (add random move to sequence)
- showTurns(function)   -   (play sequence, use javascript interval to call lights on function)
- lightsOn(function)    -   ( will light up appropriate circle)
- playerTurn(function)  -   (check to see if the player has clicked the right circle)
- showScore(function)   -   (updates the score in the DOM)

Using red/green factor process to build.

## Functions

**newGame(;**

- Reset the score to 0
- Clear the playerMoves array
- Clear the currentGame array
- Call show score function
- Call add turn function

**showScore();**

- Show the score

**addTurn();**

- Clear the playerMoves array
- Randomly add a button ID to the currentGame array
- Call showTurns function

**lightsOn();**

- Turn on light
- Turn off light

**showTurns();**

- Step through currentGame

**playerTurn**

- Check if the player move matches the computer sequence
- At the end of the sequence, increment score and add another turn
- If moves do not match, display alert and start new game

## Changelog

21/01/22

- Set HML/CSS
- Planned JavaScript functions
- Added game object, keys and testing
- Added newGame and showScore functions and testing
- Added addTurn function and testing
- Added lightsOn function and testing