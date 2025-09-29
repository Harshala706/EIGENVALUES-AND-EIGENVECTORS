# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
 Import the NumPy library using 'import numpy as np'.
### Step 2: 
Define the matrix using np.array().
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Display the eigenvalues and eigenvectors using print().
## Program:
```
#Program to find the eigen values and eigen vectors.
Developed by: B Harshala Reddy 
RegisterNumber:212224040050

import numpy as np
a = np.array([[2,2], [1,3]])
eig_value,eig_vector=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(eig_value,eig_vector))
```
## Output:
<img width="1302" height="792" alt="Screenshot 2025-09-29 223514" src="https://github.com/user-attachments/assets/c2580531-fe98-4608-aa0d-95681ab96b8b" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
