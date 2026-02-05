<img width="1176" height="154" alt="image" src="https://github.com/user-attachments/assets/836dd909-a1a8-4722-a33c-812cde8fa914" /># EIGENVALUES-AND-EIGENVECTORS
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

```
import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:

<img width="1176" height="154" alt="Screenshot 2026-02-05 142632" src="https://github.com/user-attachments/assets/f46387a8-57f3-4ecb-afa2-11cf13a3af76" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
