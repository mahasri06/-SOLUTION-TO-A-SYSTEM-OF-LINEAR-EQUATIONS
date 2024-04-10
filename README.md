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
#Developed by: Mahasri P.
#RegisterNumber:212223100029


import numpy as np
a = np.array([[1, 3], [2, 5]])
b = np.array([5,-3])
solution = np.linalg.solve(a, b)
print(solution)
```

## Output:

![Screenshot 2024-04-10 200509](https://github.com/mahasri06/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/139841897/5b94ba94-7de9-4d6c-8818-05fa2e4b7960)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

