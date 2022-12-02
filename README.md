The purpose of this project is to re-create a the classic "rock paper scissors game" on the web.

The goal is to include JavaScript on the page in 3 separate ways.

Remember to test it out by console.log() your code



Plan:
- The game will be played in a 'best 2 out of 3' scenario -
(max the user gets 3 attempts)

- Create a textbox for user to input either "rock", "paper", or "scissors"

- Once submitted - computer will count down flashing "1-Rock 2-Paper 3-Scissor 4-SHOOT!"

- After "4-SHOOT!" computer will provide their choice...

- The computer will formulate a counter variable (choice) based on the number submit attempts from user: 
    ex: 
        Attempt #1) computer will ALWAYS generate scissors.
        Attempt #2) computer will ALWAYS generate paper.
        Attempt #3) computer will ALWAYS generate rock.

- For any attempt if user has same guess as computer show "Draw"

- For 1st attempt...if user has paper for 1st attempt display "lOSER!"
    - Else user has rock display "WINNER!"

- For 2ND attempt...if user has rock for 1st attempt display "lOSER!"
    - Else user has scissors display "WINNER!

- For 3rd attempt...if user has scissors for 1st attempt display "lOSER!"
    - Else user has paper display "WINNER!