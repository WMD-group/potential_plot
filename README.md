Potential-plot
====================
A python script to takes GULP input file and plot the Buckingham and Coulomb potentials, as well as the total potential, on a single graph. 

Requirements
------------
Python

Current Status
------------
- Reads specified gulp input file 
- Defaults to GULP.gin 
- Plots the Buckingham potential and corresponding Coulombic interaction on same graph along with the total potential for the specified interaction
- Saves plots as .eps files, named after the atoms involved in that potential

Execution 
------------
python potentials.py -f file_name

Short-term goals
------------
- To add support for the Lennard-Jones potential

Disclaimer
----------
This file is not affiliated with *GULP*. Feel free to use and modify, but do so at your own risk.

