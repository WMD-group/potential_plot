Potential-plot
====================
A python script to takes GULP input file and plot the Buckingham and Coulomb potentials, as well as the total potential, on a single graph. 

Requirements
------------
Python

Current Status
------------
- Reads specified gulp file 
- Defults with GULP.gin 
- Plots the Buckingham potential and corresponding coulombic interaction on same plot along with the total potential
  for the specified interaction.
- Saves plots as eps files, named after the atoms involved in that potential

Execution 
------------
python potentials.py -f file_name

Short-term goals
------------
- To add support for the Lennard-Jones potential

Disclaimer
----------
This file is not affiliated with *GULP*. Feel free to use and modify, but do so at your own risk.

