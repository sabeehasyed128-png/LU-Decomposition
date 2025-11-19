# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Step1 : Import the numpy module to use the built-in functions for calculation
2. Step 2: Prepare the lists from each linear equations and assign in np.array()
3. Step 3: Using the scipy.linalg, we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
4. Step 4: End the program

## Program:
(i) To find the L and U matrix
```
'''
Program to find the L and U matrix using LU dec.
Developed by: SABEEHA PARVEEN.K
RegisterNumber: 25016301
''' 
import numpy as np 
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: SABEEHA PARVEEN.K
RegisterNumber: 25016301
''' 
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu,pivot = lu_factor(A)
X = lu_solve((lu,pivot),B)
print(X)
```

## Output:
<img width="1477" height="790" alt="EXP5 1" src="https://github.com/user-attachments/assets/0e718887-4365-4e56-9fd9-ab4c4d378df3" />
<img width="1471" height="609" alt="EXP5 2" src="https://github.com/user-attachments/assets/9fc5870f-c123-4e5b-8916-71b59e643118" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

