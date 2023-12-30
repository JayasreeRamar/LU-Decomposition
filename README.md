# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program.
2. Write the code appropriately.
3. Check the code.
4. Run the program.

## Program:
(i) To find the L and U matrix
```
'''
Program to find L and U matrix using LU decomposition.
Developed by: Jayasree R 
RegisterNumber: 23009250
'''
# To print L and U matrix
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
'''
Program to solve a matrix using LU decomposition.
Developed by: Jayasree R
RegisterNumber: 23009250
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv), b)
print(x)

```

## Output:
![OUTPUT](<Screenshot 2023-12-30 132504.png>)


![OUTPUT](<Screenshot 2023-12-30 132537.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

