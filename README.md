# Sudoku-Solver
 Solving sudoku puzzles
 
------------------------------------------------------------------------------------------------------------------------------------------
Executing the program opens the console with the following text:

```
Enter the filename of sudoku puzzle: 
```
There is a SudokuEasy.txt file in the folder that consists of an easy sudoku puzzle. After entering SudokuEasy.txt into the console we will see the solution.

Zeros represent blank spaces.

```sh
Enter the filename of sudoku puzzle:
SudokuEasy.txt
Initial State

|9|0|0|2|3|7|6|8|0|
|0|2|0|8|4|0|0|7|3|
|8|0|7|1|0|5|0|2|9|
|0|0|4|5|9|8|3|0|0|
|0|0|0|0|0|1|0|0|6|
|0|0|0|0|0|0|0|4|7|
|4|0|1|3|0|6|2|9|5|
|0|5|0|9|1|0|7|3|8|
|3|0|8|0|5|0|0|0|0|

Final State

|9|4|5|2|3|7|6|8|1|
|1|2|6|8|4|9|5|7|3|
|8|3|7|1|6|5|4|2|9|
|7|6|4|5|9|8|3|1|2|
|2|8|3|4|7|1|9|5|6|
|5|1|9|6|2|3|8|4|7|
|4|7|1|3|8|6|2|9|5|
|6|5|2|9|1|4|7|3|8|
|3|9|8|7|5|2|1|6|4|

Sudoku puzzle is solved!
```
## How it works
After the program is given the right .txt file it uses a basic strategy with checks for possible numbers in a row, column and block for each cell. If the puzzle is not solved, after going threw the whole puzzle adding and 
removing possible numbers to cells, it goes through the puzzle again untill it's solved or it can't be solved.

**Program would be improved and capable of solving harder puzzles only by adding other types of strategies to the code.**
