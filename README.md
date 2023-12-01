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
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
*/
```
import numpy as np
from scipy.linalg import lu
a=eval(input())
p,l,u=lu(a)
print(l)
print(u)
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
```
import numpy as np
from scipy.linalg import lu,solve
a=eval(input())
b=eval(input())
p,l,u=lu(a)
x=solve(a,b)
print(x)

## Output:
![lu decomposition](![Screenshot from 2023-12-01 13-53-30](https://github.com/premsuryas/LU-Decomposition/assets/147473858/b31beb78-05c5-4511-b966-f078453fa071)
)
![lu decompostion](![Screenshot from 2023-12-01 13-54-12](https://github.com/premsuryas/LU-Decomposition/assets/147473858/c0f07ba2-6093-4592-9f7e-bcf80d3e9195)
)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

