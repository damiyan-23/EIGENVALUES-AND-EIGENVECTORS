# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

### Step 2: 

import numpy as np 

### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 

A = np.array([[4,2],[2,4]])
values,vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

## Program:
<img width="1262" height="840" alt="image" src="https://github.com/user-attachments/assets/c4babb88-5579-49c8-8ac2-9455cc274bd6" />


## Output:
<img width="1281" height="337" alt="image" src="https://github.com/user-attachments/assets/b3071b17-d7ed-4a28-8aad-cb2973a1d184" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
