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
import numpy as np
A = np.array([[1, 2],
              [3, 4]])

inverse = np.linalg.inv(A)

print("The given matrix is:")
print(A)

print("Inverse of the matrix is:")
print(inverse)
```
## Output:

<img width="879" height="517" alt="Screenshot 2026-05-11 185808" src="https://github.com/user-attachments/assets/fd218a12-b37d-4907-b8c9-6a485395594d" />










<img width="663" height="319" alt="Screenshot 2026-05-11 185813" src="https://github.com/user-attachments/assets/23a5032e-12c1-4735-9249-3a7b47d75ba4" />







## Result:
Thus the inverse of given matrix is successfully solved using python program

