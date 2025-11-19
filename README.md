# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for find rank of a matrix
### Step 2:
Prepare the lists from each linear equation and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by: santhosh G
#RegisterNumber:25016754
import numpy as np
a=np.array( [[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(a)
print(rank)
```
<img width="1274" height="740" alt="Screenshot 2025-11-19 112119" src="https://github.com/user-attachments/assets/4b111c5b-e606-4612-b911-f68f9d44ec30" />

## Output:
<img width="1286" height="211" alt="Screenshot 2025-11-19 112146" src="https://github.com/user-attachments/assets/9429b3db-526c-4ee2-b154-abe0a0a7e6c3" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

