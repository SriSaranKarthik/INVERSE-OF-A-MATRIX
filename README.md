# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:Import the numpy module to use the built-in functions for calculation
### Step 2:Prepare the lists from each linear equations and assign in np.array()
### Step 3:Using the np.linalg.matrix_inv(), we can find the rank of the given matrix
### Step 4:End the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by:K.SRISARAN KARTHIK
#RegisterNumber:212224230275
import numpy as np 
A=np.array([[2,1,1],[1,1,1],[1,-1,2]])
result=np.linalg.inv(A)
print(result)
```
## Output:

![image](https://github.com/user-attachments/assets/9c155b88-d370-4e52-969f-6ba8d5ac15f9)

## Result:
Thus the inverse of given matrix is successfully solved using python program
