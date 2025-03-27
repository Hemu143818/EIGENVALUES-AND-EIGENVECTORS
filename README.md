# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Define the matrix 
𝐴
A.

2. Compute eigenvalues and eigenvectors using np.linalg.eig(A).

3. Extract eigenvalues.

4. Extract eigenvectors.

5. Print the eigenvalues and eigenvectors.

## Program:
~~~
import numpy as np

A = np.array([[2, 2], 
              [1, 3]])

eigenvalues, eigenvectors = np.linalg.eig(A)

print("Eigen values are", eigenvalues,"and",end=" ")
print("Eigen Vectors are", eigenvectors)
~~~

## Output:
![image](https://github.com/user-attachments/assets/055cf021-6aff-40f6-95ac-60cf4efa2691)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
