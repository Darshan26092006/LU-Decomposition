# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'
## Program:

i) To find the L and U matrix
```

Program to find L and U matrix using LU decomposition.
Developed by: Darshan V
RegisterNumber: 212224230050

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix
```

Program to solve a matrix using LU decomposition.
Developed by: Darshan V
RegisterNumber: 212224230050


import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:

i)

![Screenshot 2024-05-06 141450](https://github.com/PreethiS647/LU-Decomposition/assets/147313372/8dfd22a8-d68a-4c37-9722-2630d7885a34)

ii)

![Screenshot 2024-05-06 141502](https://github.com/PreethiS647/LU-Decomposition/assets/147313372/e4d6a2f2-ce09-4f9f-b73e-0257705c417c)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.


