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
#Developed by: Mithun Sai P
#RegisterNumber: 25008604

import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array([-9,4,-1])

x=np.linalg.solve(A,B)
print(x)
```
## Output:

<img width="1078" height="491" alt="image" src="https://github.com/user-attachments/assets/ab992d88-189e-43a6-ba93-c512636fbc49" />

<img width="897" height="240" alt="image" src="https://github.com/user-attachments/assets/deeaddc4-0ad9-4a04-ad50-3b5f30ac8e73" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

