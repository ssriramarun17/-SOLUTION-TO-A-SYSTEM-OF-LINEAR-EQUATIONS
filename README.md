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
import numpy as np

A = np.array([[1, -3],
              [3,  1]])

B = np.array([0, 10])
solution = np.linalg.solve(A, B)

print(solution)
```

## Output:
<img width="1017" height="849" alt="Screenshot 2026-02-01 144808" src="https://github.com/user-attachments/assets/471001b3-d147-429f-90b3-29cb875ba56c" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

