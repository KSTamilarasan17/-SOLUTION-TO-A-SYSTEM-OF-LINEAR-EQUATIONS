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
#Developed by: TAMILARASAN K S.
#RegisterNumber:23000080

import numpy as np
coefficients=np.array([[1,0],[3,1]])
rhs=np.array([3,10])
solution=np.linalg.solve(coefficients,rhs)

print(solution)
```
## Output:
![Screenshot 2023-11-29 204520](https://github.com/KSTamilarasan17/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/138849236/2cbcbd20-49c5-40e5-9e55-9ab47b1d2bbf)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

