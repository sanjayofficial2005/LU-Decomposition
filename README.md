# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy package
2. from scipy.linalg import lu
3. solve using scipy.linlag(variable)
4. End the program


## Program:

(i) To find the L and U matrix
```python
#Program to find L and U matrix using LU decomposition.
#Developed by: SANJAY M
#RegisterNumber: 212223230187


import numpy as np
from scipy.linalg import lu
arr=eval(input())
P,L,U=lu(arr)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix
```python
#Program to solve a matrix using LU decomposition.
#Developed by:  SANJAY M
#RegisterNumber: 212223230187


# To print X matrix (solution to the equations)

import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3,2,7],[2,3,1],[3,4,1]])
B=np.array([4,5,7])
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)
```


## Output:
![alt text](<Screenshot 2024-04-27 085537.png>)
![alt text](<Screenshot 2024-04-27 085552.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

