# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

Step 1: Import the NumPy library using import numpy as np.

Step 2: Define the given matrix using np.array() and store it in a variable.

Step 3: Using the np.linalg.eig() function, obtain two results (first is eigenvalues and second is eigenvectors) of the given matrix.

Step 4: Display the eigenvalues and eigenvectors using the print() function.


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
