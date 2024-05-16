# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by:KAVYA T
RegisterNumber:2305003004 
```
```
 # To print L and U matrix
 import numpy as np
 from scipy.linalg import lu
 A=np.array(eval(input()))
 P,L,U=lu(A)
 print(L)
 print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by:KAVYA T
RegisterNumber:2305003004 
```
```
# To print L and U matrix
 import numpy as np
 from scipy.linalg import lu_factor,lu_solve
 A=np.array(eval(input()))
 B=np.array(eval(input()))
 lu,piv = lu_factor(A)
 x=lu_solve((lu,piv),B)
 print(x)
```

## Output:
![IMG-20240513-WA0005](https://github.com/Ayvak16122005/LU-Decomposition/assets/147690197/d29876ed-e580-4b61-8c13-c3644791e65c)
![IMG-20240513-WA0007](https://github.com/Ayvak16122005/LU-Decomposition/assets/147690197/d28ca9ce-e453-41ef-b8a1-3bd2e1f65b6d)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

