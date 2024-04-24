## LU Decomposition
## AIM:
To write a program to find the LU Decomposition of a matrix.
## Equipments Required:
Hardware – PCs

Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm :
1.Read the elements of augmented matrix into arrays a and b

2.Calculate elements of L and U

3.Print elements of L and U

4.Find V by solving LV = B by forward substitution

5.Find X by solving UX = V by backward substitution

6.Print Array X as the solution
## Program:
(i) To find the L and U matrix
```python
## Program to find the L and U matrix.
Developed by: R.Sanjith
RegisterNumber: 212223230191

from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix

Program to find the LU Decomposition of a matrix.
```
Developed by: R.Sanjith
RegisterNumber: 212223230191

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```
## Output:
![Screenshot 2024-04-18 212451](https://github.com/Kamal-XO/LU-Decomposition/assets/167451460/bbc35c7d-a60b-48e9-b70e-a64d931257f9)

![Screenshot 2024-04-18 212640](https://github.com/Kamal-XO/LU-Decomposition/assets/167451460/b8b58bad-32af-4b6d-9ba5-9ba64b450c67)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

