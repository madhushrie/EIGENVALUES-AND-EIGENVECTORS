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
Prepare the lists from each linear equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```
import numpy as np
a=np.array([[2,2],[1,3]])
value,vec=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {}'.format(value,vec))
```

## Output:
![Screenshot (97)](https://github.com/user-attachments/assets/1c24a8e8-2ea4-454d-92d0-d0c2cb2e47cb)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
