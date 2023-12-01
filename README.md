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
A=[[1,-3],[3,1]]
b=np.array([0,10])
c=np.linalg.solve(A,b)
print(c)
```

## Output:
![Screenshot 2023-11-30 095650](https://github.com/Santhosh-0031/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/145551108/cc204874-8a2c-4b48-ae5e-6965907b84bc)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

