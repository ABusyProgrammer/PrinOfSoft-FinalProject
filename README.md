# Sudoku Game
The project is to design a Sudoku game on a computer interface using the Agile process

## How to play the game?
The Sudoku game is divided into 3 files: an HTML file, a CSS file and Javascript file. Go over to the repository and then click clone or download as a zip file. Extract the file and then open the Sudoku game folder and then open the `sudoku.html` file in which there you will bring up the game. When you open the game the grid is filled with some numbers randomly generated in the cells with a majority of them being blank for the user to solve. Once the game is opened, the game can be played by the user selecting a cell where a selection list will display with numbers 1-9 for the user to select. To decide what number to input, the user must follow the rules of the Sudoku game which are:
  1) Within each 3x3 quadrant, no same number can be repeated
  2) Cannot have the same number within the same row or column twice

Technology used: HTML, CSS and JavaScript

## Structure:
In the Sudoku folder, the `sudoku.html` file contains the structure of the game and the game data which includes the Javascript code that runs the application. Most of the code within this file pertains to the Javascript code. 
In the Sudoku folder, the `sudoku.css` file contains and controls the style of the of the game. This includes the color of the grid, background and font-size.

## Technical Choices: 
This program contains a 9x9 grid generated by two for loops under the function generateTable. This function sets the rows and columns of the game and then under the function generateBoard, the numbers of the game are set. Numbers that are preset change every time the game is refreshed. There are also other functions that make up the rules of the Sudoku game which involves not having a duplicate number within the same quadrant, no duplicate numbers within the same row and column, and if the rules are all satisfied, a pop up message is displayed stating "You win the game!". Finally, the game was chosen to be made using HTML, CSS and JS over java and other languages as customization was very open in HTML, CSS and JS. 

## Improvement for Future Versions:
- Instead of a drop down box to select a number, hovering over a quadrant will display the options in a circle. 
- When a user enters in a number wrong or doesn't fulfill one of the rules, the quadrant will become red
- If the user enters in a number correctly and fulfill's all rules, the quadrant will become blue 
- For the numbers that are randomly generated in the cells when the game is opened or refreshed, user's shouldn't be able to modify and edit that cell. There should be no selection list for those particular cells. 

