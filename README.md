# Minesweeper

This is an implementation of the classic Minesweeper game, created by Jon Menard. The game can be played online at https://jonmenard.github.io/games.html.

## How to play

The objective of Minesweeper is to clear a rectangular board containing hidden "mines" or bombs without detonating any of them, with help from clues about the number of neighboring mines in each cell.

The board is divided into cells, which can either be blank or contain a number indicating the number of mines in adjacent cells (including diagonals). To win the game, you must flag all the mines and reveal all the other cells. You lose the game if you reveal a cell containing a mine.

To reveal a cell, simply click on it. If the cell does not contain a mine, it will reveal the number of adjacent mines, or be blank if there are no adjacent mines. If the cell does contain a mine, the game is over and you lose.

To flag a cell as containing a mine, right-click on it. If you flag all the mines and reveal all the other cells, you win.

## Game settings

* Easy: 20 mines on a 20x30 board
* Medium: 50 mines on a 20x30 board
* Hard: 80 mines on a 20x30 board
* Expert: 120 mines on a 20x30 board


## Technologies used
The game is implemented using HTML, CSS, and JavaScript, and can be played in any modern web browser.

 
