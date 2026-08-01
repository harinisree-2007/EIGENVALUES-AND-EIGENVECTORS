# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:


Step 1: Start the program and import the NumPy library.
Step 2: Define the given matrix using numpy.array().
Step 3: Using the np.linalg.eig() function, obtain the Eigenvalues and Eigenvectors of the given matrix.
Step 4: Display the Eigenvalues and Eigenvectors and stop the program.


## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Harini Sree N
#RegisterNumber:212225230093
import os

os.environ['OPENBLAS_NUM_THREADS']='1'
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])

eigenvalues, eigenvectors=np.linalg.eig(A)

print("Eigen values are",eigenvalues, "and Eigen Vectors are",eigenvectors)


```

## Output:

<img width="1462" height="887" alt="image" src="https://github.com/user-attachments/assets/2ff42626-28a0-44e4-920a-65fc27db8729" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
