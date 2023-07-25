# INVERSE-OF-A-MATRIX
## AIM:
To write a python program to find the inverse of a matrix
## EQUIPMENTS REQUIRED:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM:
### Step1:
Import the numpy module to use the built-in functions for calculation 
### Step 2:
Prepare the lists from each linear equations and assign in np.array() 
### Step 3: 
Using the np.linalg.inv(), we can find the inverse of the given matrix.
### Step 4: 
End the program

## PROGRAM:
```
#Program to find the inverse of a matrix.
#Developed by: Daksha Subbaian
#RegisterNumber: 23003584
import numpy as np
A=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
result=np.linalg.inv(A)
print(result)
```
## OUTPUT:
![output](/output03.png)
## RESULT:
Thus the inverse of given matrix is successfully solved using python program

