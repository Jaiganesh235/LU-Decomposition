# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Assign in np.array()
3. Using the np.linalg.solve(), we can find the solutions.
4. End the program.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: S.Jaiganesh
RegisterNumber: 212222240037
*/
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: S.Jaiganesh
RegisterNumber: 212222240037
*/
import numpy as np
from scipy.linalg import lu_factor, lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![Screenshot (85)](https://github.com/Jaiganesh235/LU-Decomposition/assets/118657189/2ae084f5-563b-4313-9cec-f2c386c80695)
![Screenshot (86)](https://github.com/Jaiganesh235/LU-Decomposition/assets/118657189/15e33e08-3871-4fa5-b4f5-0b4f363d611f)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

