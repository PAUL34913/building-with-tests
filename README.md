# building-with-tests

Simple JavaScript project built using JEST and test driven development.

HTML and CSS for the project are pre-supplied in order to focus on the JavaScript and testing.

**Javascript Structure**

- game{object}              (stores game state)
- newGame(function)     -   (resets everything and starts new turn)
- addTurn(function)     -   (add random move to sequence)
- showTurns(function)   -   (play sequence, use javascript interval to call lights on function)
- lightsOn(function)    -   ( will light up appropriate circle)
- playerTurn(function)  -   (check to see if the player has clicked the right circle)
- showScore(function)   -   (updates the score in the DOM)