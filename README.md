# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Write a program to find the eigen values and vector of the matrix
### Step 2: 
get the input
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Execute the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Santhosh L
#RegisterNumber:212222100046
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(evalues,evector))
```
## Output:
![EIGENVALUES-AND-EIGENVECTORS](exp4.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
