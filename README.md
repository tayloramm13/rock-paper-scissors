The purpose of this project is to re-create a the classic "rock paper scissors game" on the web.

The goal is to include JavaScript on the page in 3 separate ways.

Remember to test it out by console.log() your code



Plan: Played completely from Console
- The game will be played in a 'best 2 out of 3' scenario -
(max the user gets 3 attempts)

- Create function getComputerChoice() and set it to randomly return 'Rock', 'Paper' or 'Scissors'
    *console.log to make sure it is returning expected output*

- Create function (with 2 parameters)that plays a single round of R.P.S - 
    - (playerSelection, computerSelection)
        *make functions playerSelection case-insensitive*
    - return string that declares the winner of the round (i.e "LOSER! Paper beats Rock")

- Create new function game() and call the playRound() function INSIDE of this function to play 5-round game that keeps score AND reports a winner/loser at the end
    *use loops to play 5 rounds*