# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. Using the lu() function in scipy.linalg module, we can find the solutions.
4. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: JAYAMANI R
RegisterNumber: 22008124
*/
import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: JAYAMANI R
RegisterNumber: 22008124
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=eval(input())
A=np.array(arr)
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)

```

## Output:
1)![2](https://user-images.githubusercontent.com/85949888/214747475-6c62f300-1499-4303-a285-b3e4b29762fd.png)
2)![3](https://user-images.githubusercontent.com/85949888/214747651-35b962d4-bc17-4159-bfd7-cdefdc0f357e.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

