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
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array([[1,3],[2, 5]])
B = np.array([5, -3])
x = np.linalg.solve(A, B)
print(x)

## Output:
<img width="1305" height="250" alt="image" src="https://github.com/user-attachments/assets/0457ae75-7567-42fc-a723-e81d3ef92411" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

