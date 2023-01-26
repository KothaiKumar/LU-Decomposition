# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. Using this formula np.array(eval(input())), we can find the solutions
4. End the program

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: Kothai K
RegisterNumber: 22006043
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
Developed by: Kothai K
RegisterNumber: 22006043
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv =lu_factor(A)
x =lu_solve((lu, piv),b)
print (x)


*/
```

## Output:
![lu](https://user-images.githubusercontent.com/121215739/214838743-7c235ffd-dcbd-42c6-8ab6-7569745eb1f3.png)
![lu 2](https://user-images.githubusercontent.com/121215739/214838897-4b4f7cd7-995c-4e92-a69a-d19e0b04fb70.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

