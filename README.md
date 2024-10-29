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
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: MABBU ADARSH
RegisterNumber: 212223100028
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U) 
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: MABBU ADARSH
RegisterNumber: 212223100028
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X) 
*/
```

## Output:
![lu decomposition]()
![image](https://github.com/user-attachments/assets/436bfee9-ef5f-47a8-9192-9ded38292090)
![image](https://github.com/user-attachments/assets/270a6404-29b8-46af-85d7-20df3bc05293)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

