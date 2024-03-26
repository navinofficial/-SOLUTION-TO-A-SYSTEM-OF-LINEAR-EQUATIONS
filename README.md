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


#Developed by   : Navinkumar v
#RegisterNumber : 212223230141

import numpy as np
a = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
b = np.array([-9,4,-1])
solution = np.linalg.solve(a,b)
print(solution)
```
## Output:
![Screenshot 2024-03-26 141114](https://github.com/Bharathraj2006/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/152376845/bf9ea509-c393-4b34-9601-45715334ba83)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

