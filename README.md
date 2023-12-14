# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. start the program
2. get the approximate
3. using the variable get the values appropriately
4. end the program
   

## Program:
(i) To find the L and U matrix
```
*/
Program to find the L and U matrix.
Developed by: YENUGANTI PRATHYUSHA
RegisterNumber: 23009045
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
Program to find the LU Decomposition of a matrix.
Developed by:YENUGANTI PRATHYUSHA 
RegisterNumber:23009045
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
X=lu_solve((lu,piv),b)
print(X)
 
*/
```

## Output:

![image](https://github.com/prathyusharavi/LU-Decomposition/assets/147474424/52219124-68dd-46b0-9efc-f71b076bfc4e)
![image](https://github.com/prathyusharavi/LU-Decomposition/assets/147474424/390a6f60-33df-4025-8dd0-2ddc933ada8c)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

