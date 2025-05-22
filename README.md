# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm 1:
i)
step1
find the l and u matirx by using numpy and linalg from scipy

step2
print the l matrix and u matirx

step3
find the lu decomposition by using numpy and lu_factor and lu_solve

step4
print the the following matrix

## Algorithm 2:
 
ii)
step1
In second program can import lo factor and lu selve from python library as same as in second program.

step2
Get the input from user in the form of nested list to compute numpy array format and declare it for both the variables

step3
Step Create the variable to Use inputted array to compute of lu, factor of matrix varaible.

step4
Step Create the new variable for a solve to compute of x variable and b' variable.

step5
Steps Print the corresponding variable (solution) to get the output

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: vishwa v
RegisterNumber: 212224110062
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: vishwa v
RegisterNumber: 212224110062
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
piv,lu=lu_factor(A)
result=lu_solve((piv,lu),B)
print(result)
```

## Output:
![](<Screenshot 2025-05-11 194402-1.png>)
![](<Screenshot 2025-05-11 194414-2.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

