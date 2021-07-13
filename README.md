# Lab 11 - Numpy
## Author: Tony Regalado

## Collaborators: Anthony William, Kevin Henry

## Link to GitHub
[GitHub](https://github.com/Edward-Regalado/chess_board)

## Link to Google Colab
[Google Colab](https://colab.research.google.com/drive/1-h9skOFX1cp9cB46_qXoIBl4xF_J42n6#scrollTo=P3u5hye9cnN2)

## Overview
- Build a 8 by 8 chess board grid with alternating black and white squares. The two queens are red and blue sqaures.

## Feature Tasks & Requirements
Render different chess boards with one red and blue queen at different coordinates. In addition to displaying the board you'll need to identify if the queens are "under attack" based on their position.

## Implementation
* Define a ChessBoard class - should contain an 8x8 grid - Each cell in grid should have a color represented in RGB format. - black = (0,0,0) - white = (1,1,1) - blue = (0,1,1) - red = (1,.2,0)
* should have add_red method that accepts a row and column as input which colors corresponding cell.
* should have add_blue method that accepts a row and column as input which colors corresponding cell.
* should have render method that displays the chess board on screen with red and blue shown in correct locations
* should have is_under_attack method that return boolean if red is under attack by a blue piece horizontally, vertically or diagonally

## Tests
* queens on same row should be “under attack”
* queens on same column should be “under attack”
* queens on same diagonal should be “under attack”
* queens with any other coordinates should NOT be “under attack”
