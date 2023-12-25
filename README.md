# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy module to use the bulit-in function for calculation 
### Step 2: 
prepare the lists from each linear equation and assingn in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.
## Program:
  ```
  #Program to find the eigen values and eigen vectors.
#Developed by: M GAYATHIRI ROSHINI
#RegisterNumber:23006823
import numpy as np
a=[[-2,2,-3],[2,1,-6],[-1,-2,0]]
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
  ```
## Output:
![image](https://github.com/23006823/EIGENVALUES-AND-EIGENVECTORS/assets/138971409/d902b64a-69e3-4245-b2ab-646963ccd55a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
