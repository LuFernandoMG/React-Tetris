# About this project

We have all played the classic video game Tetris. In this version, you can play it in your browser in the comfort of your computer in your free time (or while you work, I won't tell anyone ;)).

The game is structured entirely in React and uses a move() function that allows us to capture and identify the buttons that have been pressed. This helps us to determine the behavior of the piece with respect to the game board (and to know its limits) and control it.

In this application, we developed several CustomHooks to facilitate our rendering of each of the "pixels" of the board and how the pieces should behave.

In addition, to improve the interactivity, we established a level system, where after every ten rows are eliminated, you will go up a level, so the speed of fall of the pieces will be higher.

Note: It is an application 100% managed in the Frontend, so it is impossible to save the scores (I decided not to use LocalStorage for this).

## Controls

Use your arrow keys! ⬆️ ➡️ ⬇️ ⬅️

## [Play!](https://tetris-mu-beige.vercel.app/)
