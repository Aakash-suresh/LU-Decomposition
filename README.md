# File 5-A  LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy library using import statement.
2. From scipy package import lu().
3. Get input from user and pass it as an array.
4. Get P, L U martix using lu().
5. print L and U matrix.

## Program:
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Aakash S
RegisterNumber: 21500657
*/
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

## Output:
![Output 1](DDD1.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

# File 5-B  LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy library using import statement.
2. From scipy package import lu_factor() and lu_solve().
3. Get two inputs from user and pass it as matrix array.
4. find lu and pivot value of first marix using lu_factor().
5. find solution of the matrix by using lu_solve() by passing lu, pivot values as first argument and second matrix as second argument.
6. print the solution.

## Program:
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Aakash S
RegisterNumber: 21500657
*/
```
import numpy library using import statement.
From scipy package import lu_factor() and lu_solve().
Get two inputs from user and pass it as matrix array.
find lu and pivot value of first marix using lu_factor().
find solution of the matrix by using lu_solve() by passing lu, pivot values as first argument and second matrix as second argument.
print the solution.

## Output:

![Output 2](DDD2.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

