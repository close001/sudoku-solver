# Sudoku-Solver
**INTRODUCTION**\
This program uses GAC algorithm which is a backsearch algorithm that uses pruning to solve a sudoku puzzle.

**SETUP**\
Note that this setup is done on Windows. Though some specifics may vary, it will be mostly similar on all OSes.
1. First, you need to have JDK installed on your computer to compile and run the files.
2. Download all the java files in the repository in one folder. 
3. Open up your command line and go to the folder in which you downloaded the files.
4. Type `javac Main.java' to compile the files.

**EXECUTING THE PROGRAM**\
First, run the program using the command `java Main`. When the program is executed, you will be asked to input sequentially each row on the board you want to solve.

For example, if the n_th row has |1|2|3| |5| |7|8|9|, you will input '123050789' and press enter.\
Note that there is no space between each column and empty columns are given a 0.

When you input all the rows, the program will display the answer to the original sudoku board.



