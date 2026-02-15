# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: Praveen Raj.R
#RegisterNumber: 212224230207
import numpy as np

A = np.array([[2, -3, 0],
              [2, -5, 0],
              [0,  0, 3]])

eigen_values, eigen_vectors = np.linalg.eig(A)

print("Eigen values are", eigen_values, "and Eigen Vectors are", eigen_vectors)
```




## Output:
<img width="1368" height="990" alt="image" src="https://github.com/user-attachments/assets/0459dd1c-ef6f-4ff6-9551-a553e4fa017e" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
