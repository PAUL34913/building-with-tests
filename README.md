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

**newGame();**

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

**playerTurn();**

- Check if the player move matches the computer sequence
- At the end of the sequence, increment score and add another turn
- If moves do not match, display alert and start new game

**Additional Testing**

- What if the player clicks a button before the game has started?
- What if the players clicks a button during the sequence?
- Set another value in the game state.
- Create a new key called turnInProgress that can be true or false.

## Changelog

21/01/22

- Set HML/CSS
- Planned JavaScript functions
- Added game object, keys and testing
- Added newGame and showScore functions and testing
- Added addTurn function and testing
- Added lightsOn function and testing

22/01/22

- Added showTurns function and testing.
- Added playerTurn function and testing.

23/01/22

- Added turnNumber and lastButton to game object.
- Finished newGame function and testing.
- Completed additional testing for turnNumber and lastButton.
- Project complete.
