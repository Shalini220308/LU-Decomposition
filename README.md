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
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input))
P,L,U = lu(A)
print(L)
print(U)
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu,pivot = lu_factor(A)
x = lu_solve((lu,pivot),B)
print(x)

## Output:
![lu decomposition]()
<img width="1189" height="455" alt="Screenshot 2025-10-16 135644" src="https://github.com/user-attachments/assets/f8d231b7-db2c-4cf0-b090-5c51c64fb797" />
<img width="879" height="189" alt="Screenshot 2025-10-16 135701" src="https://github.com/user-attachments/assets/f5b9cfe3-72ba-4af7-92a0-975a818b0c65" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

