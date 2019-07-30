# Sudoku-Solver
**INTRODUCTION**\
This program uses GAC algorithm which is a back search algorithm that uses pruning to solve a sudoku puzzle.

**SETUP**\
Note that this setup is done on Windows. Though some specifics may vary, it will be mostly similar on all OSes.\
1. First, you need to have JDK installed on your computer to compile and run the files.
2. Download all the files in one folder. 
3. Open up your command line and go to the folder in which you downloaded the files.
4. Type `javac Main.java' to compile the files.

**EXECUTING THE PROGRAM**\
The main driver for the memory simulator, _sim.c_ reads memory reference traces. For each line in the trace, the program asks for the simulated physical address that corresponds to the given virtual address by calling _find_physpage_, and then reads from that location. If the access type is a write ("M" for modify or "S" for store), it will also write to the location.

The simulator is exectued as

`./sim -f <tracefile> -m <memory size> -s <swapfile size> -a <replacement algorithm>`

where memory size and swapfile size are the number of frames of simulated physical memory and the number of pages that can be stored in the swapfile respectively. 


