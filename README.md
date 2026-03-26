# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2.Get input from user and print L and U matrix by 'print' .
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable
4.print the variable 'X'

## Program:
Developed by: INDHUJA.K

RegisterNumber: 212225040133

(i) To find the L and U matrix
```
Developed by: SUBITHA S
RegisterNumber: 212225040432
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
Developed by: SUBITHA S
RegisterNumber: 212225040432
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
```
## Output:

<img width="646" height="170" alt="image" src="https://github.com/user-attachments/assets/9bb077d3-1e92-4590-92af-1eb25c9bf570" />

<img width="895" height="347" alt="image" src="https://github.com/user-attachments/assets/e68f71b5-d6d0-4f9a-b307-5a86981f5a39" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

