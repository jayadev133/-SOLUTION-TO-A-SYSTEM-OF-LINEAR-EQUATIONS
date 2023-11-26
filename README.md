# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:  Import the NumPy library
Import the numpy module to use the built-in functions for calculation
### Step 2:  Input the coefficients matrix (A) and the constants vector (B)
Prepare the lists from each linear equations and assign in np.array()
### Step 3:  Use NumPy's linear algebra solver to find the solution
Using the np.linalg.solve(), we can find the solutions.
### Step 4:  Display the solution
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: JAYADEV PALLINTI
#RegisterNumber:23007677
import numpy as np
A=[[1,-3],[3,1]]
B=np.array([0,10])
C=np.linalg.solve(A,B)
print(C)
```

## Output:
![Screenshot 2023-11-26 140132](https://github.com/jayadev133/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/150319465/5301a8ed-eb39-44d5-8a58-7ce735febd0c)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

