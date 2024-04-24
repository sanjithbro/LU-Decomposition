# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```python
Program to find the L and U matrix.
Developed by: R.Sanjith
RegisterNumber: 212223230191
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```python
Program to find the LU Decomposition of a matrix.
Developed by: R.Sanjith
RegisterNumber: 21222323191
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
```

## Output:
![Screenshot 2024-04-18 212451](https://github.com/sanjithbro/LU-Decomposition/assets/167451460/e075e51a-7acc-4145-be33-705a96c0da7b)

![Screenshot 2024-04-18 212640](https://github.com/sanjithbro/LU-Decomposition/assets/167451460/d93bf98e-ad24-4e48-99de-2864074533f7)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

