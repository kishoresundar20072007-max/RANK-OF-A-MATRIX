# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:  Import the NumPy module to perform matrix operations.
### Step 2: Create the given matrix using `np.array()` and store it in a variable.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:  Display the rank of the matrix and end the program.

## Program:
```
#Program to find the rank of a matrix.
#Developed by: K.Sundar
#RegisterNumber: 212225040438
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=([[1, 2, 3], [3, 6, 9]])
rank=np.linalg.matrix_rank(A)
print(rank)

```
## Output:
<img width="1347" height="880" alt="image" src="https://github.com/user-attachments/assets/73b4be04-bdf2-4c7e-ae90-28d7f9242cf0" />


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program
