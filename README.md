# EIGENVALUES-AND-EIGENVECTORS

## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step1 : 
Import numpy
### Step 2:
Assign values for the array 
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the eigen values and vectors

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: Nithyaa sri S S
#RegisterNumber:22008434
import numpy as np
a=np.array([[2,2],[1,3]])
Values,Vectors=np.linalg.eig(a)
print("Eigen values are",Values,"and Eigen Vectors are",Vectors)
```

## Output:
![](eigen%20values.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
