# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1 : import num py
## Step 2: use an array function
## Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
## Step 4: then print the eigen value
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: anandhamoorthy.k
#RegisterNumber:212222100004
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {}'.format(values,vectors))
```
## Output:
![Screenshot 2023-06-08 124324](https://github.com/AnandhamoorthyKarthikeyan/EIGENVALUES-AND-EIGENVECTORS/assets/119475998/97b731e1-3ebf-4355-95f9-d917fd1a19c7)
![Screenshot 2023-06-08 124341](https://github.com/AnandhamoorthyKarthikeyan/EIGENVALUES-AND-EIGENVECTORS/assets/119475998/50b45c9f-8217-4a71-862c-5af787730819)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
