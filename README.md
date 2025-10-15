# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation.
### Step 2:Assign np.array() 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:end the program 

## Program:
~~~python
#Program to find the eigen values and eigen vectors.
#Developed by: SANTHOSH R
#RegisterNumber: 212224230249

import numpy as np
A = [[-2,2,-3],[2,1,-6],[-1,-2,0]]
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
~~~
## Output:
<img width="1312" height="959" alt="Screenshot 2025-10-15 184047" src="https://github.com/user-attachments/assets/d24f94fd-95fd-47dd-a9e1-a704956b87c4" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
