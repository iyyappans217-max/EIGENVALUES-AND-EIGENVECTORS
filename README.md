# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy library to perform matrix operations.
### Step 2: Define the matrix using a 2-D NumPy array.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the eigenvalues and eigenvectors as the output.

## Developed by: IYYAPPAN S   
## RegisterNumber:    212225230108
## Reference Number :  25014014

## Program:
```
#Program to find the eigen values and eigen vectors.

import numpy as np
A = np.array([[-2,  2, -3],[ 2,  1, -6],[-1, -2,  0]])
values,vectors = np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```


## Output:
<img width="1213" height="279" alt="image" src="https://github.com/user-attachments/assets/777f65a9-c80b-486e-8b54-c97735556126" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program....
