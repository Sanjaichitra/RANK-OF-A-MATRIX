# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
import the numpy module to use the built-in function for calculation
### Step 2: 
Prepare the list from each linear eqaution and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
Using the np.linalg.matrix_rank(), we can find the solutions

## Program:
 # Program to find the rank of a matrix.
 # Developed by:SANJAI S
 # Register Number:23013614
~~~
import numpy as np
A = np.array([[3,2,5],[1,1,2],[3,3,6]])
rank = np.linalg.matrix_rank(A)
print(rank)
~~~

## Output:
![Screenshot 2023-12-16 152451](https://github.com/Sanjaichitra/RANK-OF-A-MATRIX/assets/144870518/26d4b62c-7426-4cf6-9e97-7c3d8ada4b22)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

