# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :  To find inverse of a matrix using python programming
### Step 2: Import numpy as np.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print result

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Srinidhi senthil
#RegisterNumber:22001408
import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![Screenshot (14)](https://github.com/tharikasankar/EIGENVALUES-AND-EIGENVECTORS/assets/119475507/50e8f1ea-4a94-4c0d-8e3f-2ec4b3f61a3e)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
