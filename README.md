# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1:
Import the numpy module to use the build-in function for calculation

Step 2:
Prepare the lists from each linear equations and assign in np.array()

Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

Step 4:
End the program 
## Program:
#Program to find the rank of a matrix.
#Developed by: Kesav KM
#RegisterNumber: 212224110031

import numpy as np
A = np.array([[3, 2, 5], 
              [1, 1, 2], 
              [3, 3, 6]])
rank = np.linalg.matrix_rank(A)
print("The rank of the matrix is:", rank)

## Output:
![Screenshot 2025-03-27 203117](https://github.com/user-attachments/assets/b6b36490-bd78-42c1-9d3d-2e24bf1e0aaf)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

