# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library using import statement.
2.From scipy package import lu().
3.Get input from user and pass it as an array.
4.Get P, L, U matrix using lu()
5.Print L and U matrix
   

## Program:
(i) To find the L and U matrix.
```
'''Program to find L and U matrix using LU decomposition.
Developed by:A.BHAGATHKRISHNA 
RegisterNumber: 23002963
'''
from scipy.linalg import lu
import numpy as np

arr=eval(input())
A=np.array(arr)
p,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by:A.BHAGATHKRISHNA
RegisterNumber: 23002963
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)

```

## Output:
![Screenshot 2023-12-29 040316](https://github.com/Bhagath118/LU-Decomposition/assets/147473779/fbe39081-3f7b-480c-862d-f9110d1c42c2)
![Screenshot 2023-12-29 040158](https://github.com/Bhagath118/LU-Decomposition/assets/147473779/5d4608fa-1361-43ce-9550-7b990a7352c3)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

