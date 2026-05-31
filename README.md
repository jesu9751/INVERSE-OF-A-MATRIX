# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: 
### Step 4: 

## Program:
```

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

# Given matrix
matrix = np.array([[1, 0, 3],
                   [-1, 2, -2],
                   [2, 3, -1]])

# Find inverse of matrix
inverse_matrix = np.linalg.inv(matrix)

# Print result
print(inverse_matrix)
```
## Output:

<img width="957" height="842" alt="image" src="https://github.com/user-attachments/assets/fe34e709-b2ab-4d2e-8841-779cbe89496b" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

