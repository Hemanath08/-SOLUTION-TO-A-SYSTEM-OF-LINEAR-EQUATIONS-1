# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: HEMANATH.K
#RegisterNumber: 212223100012

import numpy as np
c = np.array([[1,3],[2,5]])
d = np.array([5,-3])
solution = np.linalg.solve(c,d)
print(solution)
```
## Output:
![EXP 1 Output](https://github.com/Hemanath08/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS-1/assets/151807176/b30ee456-9f07-45a8-bd0d-7b5e13e23c5c)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

