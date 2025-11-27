# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. From scipy package import lu().
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. Print L and U matrix

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Abdul Rahim .M
RegisterNumber: 25015778
*/
```
import numpy as np

from scipy.linalg import lu           
A=np.array(eval(input()))        
P,L,U=lu(A)        
print(L)      
print(U)       


```
(ii) To find the LU Decomposition of a matrix

/*
Program to find the LU Decomposition of a matrix.
Developed by: Abdul Rahim .M
RegisterNumber: 25015778
*/
```
import numpy as np

from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)

## Output:

<img width="1146" height="738" alt="image" src="https://github.com/user-attachments/assets/8eb50ce5-0a3f-4822-9612-37115bc9d601" />
<img width="1456" height="584" alt="image" src="https://github.com/user-attachments/assets/e3628aed-53a5-44c3-9426-d5134c1deb7a" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

