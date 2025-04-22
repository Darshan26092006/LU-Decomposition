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
![Screenshot 2025-04-22 113515](https://github.com/user-attachments/assets/3abf22b7-3219-4b97-8c52-0790e04b8a44)


ii)

![Screenshot 2025-04-22 113614](https://github.com/user-attachments/assets/9b8b4267-2e8d-4c64-b78a-930fec0cf9af)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.


