# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculation
### Step 2:
Prepare the lists from each linear equations and assign in np.array()
### Step 3:
Using the np.linalg.solve(),we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the inverse of a matrix.
#Developed by:JESUBALAN.A 
#RegisterNumber:23013427

import numpy as np
A=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
inverse=np.linalg.inv(A)
print(inverse)
```
## Output:
![Ex 3](https://github.com/Jesubalan19/INVERSE-OF-A-MATRIX/assets/144979294/8a9ef29c-faf8-4303-b217-74b0b09876d0)

## Result:
Thus the inverse of given matrix is successfully solved using python program

