# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy library as np
2. create a matrix using np.array
3. using scipy.linalg..lu() find L and U,also using scipy.linalg.li_solve() get theresult for LU decomposition
4. get the output and end the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: dharshiniyaa ks
RegisterNumber: 23014039
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: dharshiniyaa ks
RegisterNumber: 23014039
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
*/
```

## Output:
![Annotation 2023-12-25 233020](https://github.com/DHARSHINIYAA/LU-Decomposition/assets/149560172/6df52d1b-74bf-486a-8b29-9e9c2aae6fd5)
![Annotation 2023-12-25 233050](https://github.com/DHARSHINIYAA/LU-Decomposition/assets/149560172/8bc1b32c-fab7-4dfd-b64f-8f2ba0aa7385)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

