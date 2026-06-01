# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :  Import the numpy module to use the built-in functions for calculation  
### Step 2:  Prepare the lists from each linear equations and assign in np.array()
### Step 3:  Using the np.linalg.matrix_inverse(), we can find the inverse of the given matrix.
### Step 4:  End the program

## Program:
```

#Program to find the inverse of a matrix.
#Developed by: ASHLEY ANTONY
#RegisterNumber: 212225220013
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrixA=np.array([[6,2,3],[3,1,1],[10,3,4]])
res=np.linalg.inv(matrixA)
print(res)
```
## Output:


<img width="619" height="389" alt="WhatsApp Image 2026-06-01 at 9 34 47 AM" src="https://github.com/user-attachments/assets/9357c4cb-ccee-41ec-a7a6-be9dcc78c0cc" />


## Result:
Thus the inverse of given matrix is successfully solved using python program

