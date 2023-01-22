# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. get the input from user
3. use array function 
4. assign variables to array function to get the result.

## Program:
```
Program to find L and U matrix using LU decomposition.
Developed by:SABARI S 
RegisterNumber:22008698
import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```

## Output:
![Screenshot_20230122_123124](https://user-images.githubusercontent.com/118660461/213904838-8694e035-779d-4785-9dec-42e56c9dcd99.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

