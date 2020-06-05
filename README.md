# Sudoku-Solver

This Sudoku solver project uses python and the backtracking algorithm to find a solution to any solvable Sudoku board.  

  It includes two python programs
  
       - Graphical GUI 	  
       - Text based version.

## (1) For GUI :- 

	(1) For this GUI to work it must be inside the same directory as the file called GUI_solver.py 
  
	(2) You must also have pygame installed on your system.
		- Either import pygame package in your PyCharm IDE 
		- Or If want to run above code directly using python in cmd.
		- Run below command in cmd if pygame not installed.
		- "py -m pip install -U pygame --user"

	(3) After installation of pygame run GUI.py to play Sudoku.


### Instructions for Sudoku-GUI-Solver
	- Click a box and hit the number on your keyboard to insert a number in that particular box.
	- To confirm that value press the ENTER key on that box. 
	- To delete the inserted number in a particular box, select it and click DEL on keyboard.
	- Finally, if you want to solve the Sudoku board automatically press SPACE, sit back and watch the algorithm run.

## (2) For Text based version :-  
  - Run Sudoku-Text-Solver.py 
		
#  About Backtracking   

 Backtracking is simply reverting back to the previous step or solution as soon 
 as we determine that our current solution cannot be continued into a complete one.
 
 We will use this principle of backtracking to implement our algorithm.
 
# Algorithm  

### Starting with an incomplete board: 
1. Find some empty space   
2. Attempt to place the digits 1-9 in that space   
3. Check if that digit is valid in the current spot based on the current board.
 > 1. If the digit is valid, recursively attempt to fill the board using steps 1-3.  
 > 2. If it is not valid, reset the square you just filled and go back to the previous step.   
4. Once the board is full by the definition of this algorithm we have found a solution.  



