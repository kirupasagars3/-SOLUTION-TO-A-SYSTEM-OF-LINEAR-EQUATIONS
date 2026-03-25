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
A = np.array([[1, 3], [2, 5]])
B = np.array([5, -3])
solution = np.linalg.solve(A, B)
solution = np.round(solution, 1)
print(solution)
```

<img width="1463" height="869" alt="Screenshot 2026-03-25 102549" src="https://github.com/user-attachments/assets/67c9d3de-fdaa-4308-9161-90da5111d5aa" />

## Output:
<img width="1313" height="339" alt="Screenshot 2026-03-25 102607" src="https://github.com/user-attachments/assets/241615fc-6e4f-4066-893b-d40931b658b5" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

