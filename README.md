# LU Decomposition 
EX 05 LU Decomposition
Date: 13.09.2023
## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm 
1.Import numpy library using import statement.
2.From scipy package import lu().
3.Get input from user and pass it as an array.
4.Get P, L, U matrix using lu()
5.Print L and U matrix
## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: PRAVEEN V
RegisterNumber: 23013808
'''
import numpy as np
from scipy.linalg import lu
a=eval(input())
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: PRAVEEN V
RegisterNumber: 23013808
'''
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```
## Output:
![Screenshot 2023-11-18 095524](https://github.com/praveenv23013808/LU-Decomposition/assets/145824728/a4fa8fa2-0017-49f8-83d2-8d43117da1c1)
![Screenshot 2023-11-18 095607](https://github.com/praveenv23013808/LU-Decomposition/assets/145824728/f3360c6e-d9a8-40ab-9283-bbc59f324b41)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

