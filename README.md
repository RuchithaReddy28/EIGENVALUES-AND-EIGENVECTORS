# EIGENVALUES-AND-EIGENVECTORS

## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
### Step1 : 
 Import the numpy module to use the built-in functions for calculation.

### Step 2: 
Prepare the lists for each linear equations and assign array in np.array().

### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 
End the program.

## Program:

#Program to find the eigen values and eigen vectors.

#Developed by:A.Ruchitha Reddy

#RegisterNumber:21005032

import numpy as np

A=np.array([[2, -3, 0],[2, -5, 0],[0, 0, 3]])

values,vectors=np.linalg.eig(A)

print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors)

## Output:
![output](https://github.com/RuchithaReddy28/EIGENVALUES-AND-EIGENVECTORS/blob/main/Screenshot%20(20).png?raw=true)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
