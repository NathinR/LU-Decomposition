# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import the numpy module to use built-in functions for calculations 
2. Assign in np.array()
3. Using the np.linalg.slove(),we can find the solutions.
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Nathin R
RegisterNumber: 22008510
*/
```
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
Developed by: Nathin R
RegisterNumber: 22008510

*/
```
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
```

## Output:
![lu decomposition](LUDecomposition.png)
![lu decomposition](LUDecomposition2.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

