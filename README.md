# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
   
2.Get input from user and print L and U matrix by 'print' .

3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.

4.print the variable 'X'

## Program:
(i) To find the L and U matrix
```python
Program to find the L and U matrix.
Developed by:BHUMIREDDY LAKSHMI VARDHAN REDDY 
RegisterNumber:23009662 
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```python
Program to find the LU Decomposition of a matrix.
Developed by: BHUMIREDDY LAKSHMI VARDHAN REDDY
RegisterNumber: 23009662
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```
## Output:
![LU1](https://github.com/BhumireddyLakshmivardhanreddy/LU-Decomposition/assets/148514637/efab1ef0-b4e8-4c37-9b4d-7ac37a514ee5)
![LU2](https://github.com/BhumireddyLakshmivardhanreddy/LU-Decomposition/assets/148514637/ef1f8974-8370-442d-b578-7a91413bf539)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

