# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:
Start the program.

### Step 2:
Import the necessary libraries: numpy for numerical operations and scipy.linalg for LU decomposition functions.

### Step 3:
Get the input matrix (and the constant vector b if solving a system of equations).

### Step 4:
Use lu() to get the Lower (L) and Upper (U) triangular matrices.

### Step 5:
Use lu_factor() and lu_solve() if solving a system of linear equations (Ax = b).

### Step 6:
Print the L and U matrices or the solution vector X.

### Step 7:
End the program.

## Program:
(i) To find the L and U matrix
/*
```
Program to find L and U matrix using LU decomposition.
Developed by: Dashvin S
RegisterNumber: 212224100008


import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
*/

(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: DASHVIN S
RegisterNumber:212224100008

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu,piv=lu_factor(A)
X = lu_solve((lu,piv),b)
print(X)

*/
```

## Output:
![image](https://github.com/user-attachments/assets/0d807141-9f7b-4ab7-97ea-d6b2f9876894)

![image](https://github.com/user-attachments/assets/1d7e8619-3269-4817-9107-1cf02525d3ee)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

