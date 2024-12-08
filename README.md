# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program:
```
#Program to find the rank of a matrix.
#Developed by: Sharma R
#RegisterNumber: 24900539

import numpy as np

def find_matrix_rank(matrix):
    # Convert the matrix to a NumPy array
    np_matrix = np.array(matrix)
    
    # Use NumPy's matrix rank function
    rank = np.linalg.matrix_rank(np_matrix)
    return rank

# Define the matrix
matrix = [[5, -3, -10], [2, 2, -3], [-3, -1, 5]]

# Find and print the rank
rank = find_matrix_rank(matrix)
print(rank)
```

## Output:
![alt text](image.png)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

