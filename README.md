# Minesweeper and Minesweeper AI

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

## AI Solver

In additon to the game, this repository contains the code for an AI solver 


The Minesweeper solver employs several algorithms to solve puzzles. A simple algorithm based on adjacent mine counts is used to identify safe squares and bombs, and this approach is effective for many puzzles that can be solved using basic logic. In more complex puzzles, the solver uses a brute force permutation algorithm that generates all possible combinations of unopened cells. For each combination, the algorithm simulates opening all of the cells and checks whether any contain a mine. If no mines are found, the combination is considered to contain a safe square. Finally, the solver uses a probability calculator that considers factors such as the number of adjacent mines and unopened cells, as well as the frequency of bombs appearing in squares during the brute force solution. This information is used to make informed decisions about which cells to open or flag as bombs. By integrating these algorithms, the Minesweeper solver is able to solve a wide range of puzzles. However, it's worth noting that there may still be some puzzles that are impossible for the solver to solve.

The AI solver is activated by pressing the solve button at the top right

## Technologies used
The game is implemented using HTML, CSS, and JavaScript, and can be played in any modern web browser.

 
