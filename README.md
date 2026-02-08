# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step 1: Input the matrix
## Step 2: Convert matrix into row echelon form
## Step 3: Apply elementary row operations
## Step 4: Identify non-zero rows
## Step 5: Count non-zero rows
## Step 6: Display the rank of the matrix 
## Program:
```
#Program to find the rank of a matrix.
#Developed by: S.satheeswari 
#RegisterNumber: 25017493
# The number of linearly independent rows or columns in a matrix
# is known as its rank
import numpy as np
A=[[5,-3,-10],[2,2,-3],[-3,-1,5]]
rank=np.linalg.matrix_rank(A)
print(rank)
```
## Output:

<img width="578" height="387" alt="Screenshot 2026-02-08 204420" src="https://github.com/user-attachments/assets/b66e386d-cc0e-4dc0-bfef-bddf63230661" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

