# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from the matrix and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: 
#RegisterNumber:
import numpy as np
m=([[2,2],[1,3]])
w,v=np.linalg.eig(m)
print("Eigen values are",w,"and Eigen Vectors are",v)
```
## Output:
<img width="664" alt="289771155-0d47083e-ec9a-47bf-a21f-88ab7a0813ae" src="https://github.com/Naveen1825/EIGENVALUES-AND-EIGENVECTORS/assets/138969868/f80f665a-7173-4a2a-9df7-29c89b26816f"><br>
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
