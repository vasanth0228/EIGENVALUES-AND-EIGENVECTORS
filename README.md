# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1 : 
we have imported numpy which is needed.
## Step 2: 
we have created a matrix using np.array with different values in it.
## Step 3: 
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
## Step 4: 
finally,print the values of the eigen values and eigen vectors.
## Program:
Program to find the eigen values and eigen vectors.
```
Developed by: VASANTH KUMAR V 
RegisterNumber:2305002027
import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print("Eigenvalues are {} and Eigen vectors are {}".format(values,vectors))
```
## Output:
![WhatsApp Image 2024-05-10 at 11 54 23_baad9bbf](https://github.com/vasanth0228/EIGENVALUES-AND-EIGENVECTORS/assets/155505264/08616587-48b9-46f2-9c44-2c2e1b3c6776)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
