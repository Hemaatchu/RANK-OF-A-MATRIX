# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation.
### Step 2:
Prepare the lists from each equation and assign in np.array
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
end the program

## Program:
```
#Program to find the rank of a matrix.
#Developed by: 
#RegisterNumber:
import numpy as np

# Define the matrix
matrix = np.array([[3, 2, 5],
                   [1, 1, 2],
                   [3, 3, 6]])

# Find the rank of the matrix
rank = np.linalg.matrix_rank(matrix)

print("", rank)
```
## Output:
![maths2](https://github.com/Hemaatchu/RANK-OF-A-MATRIX/assets/147328300/2d34157b-4eac-4fea-9132-e159ad0f1d90)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

