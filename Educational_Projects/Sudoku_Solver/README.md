# Sudoku Solver 
This is a [Tech with Tim](https://www.youtube.com/c/TechWithTim) tutorial at this [link](https://www.youtube.com/playlist?list=PLzMcBGfZo4-kE3aF6Y0wNBNih7hWRAU2o)
Excludes the GUI Section

## Description and Examples
I'm using the first example at [this link](https://sandiway.arizona.edu/sudoku/examples.html)

This project is a sudoku solver using the [backtracking](https://en.wikipedia.org/wiki/Sudoku_solving_algorithms#cite_note-difficult_17_clue-1) algorithm

## Further Improvements (My own ideas)
Make it easier to change your board (Done)

Issues: 

The solve function doesn't work with inputted values (Solved)
This was because the input function makes value strings so to solve this just wrap the function in an int function

Try and make a gui that allows the user to input, edit or delete values from the empty squares and show the process of the backtracking taking place

I'm going to use the [tkinter](https://docs.python.org/3/library/tkinter.html) module for this GUI

Issues:
