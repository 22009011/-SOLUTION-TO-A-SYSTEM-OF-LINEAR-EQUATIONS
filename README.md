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
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array([-9,4,-1])
result=np.linalg.solve(A,B)
print(result)

```

## Output:
![Screenshot 2023-03-18 at 09-07-32 Exp -01-CR- Solving System of linear equations Attempt review](https://user-images.githubusercontent.com/118343461/226083031-6e8d6eec-edfa-460e-ac16-d0c33b34267b.png)
## Result: 
Thus the solutions for the linear equations are successfully solved using python program

