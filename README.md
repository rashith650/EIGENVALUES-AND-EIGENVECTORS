# DATE:
# EX 4 EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step 1: get the input from user
## Step 2: import math and initialise the two values
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
## Step 4:print the values in format

## Program:
```#Developed by: Mohamed Rashith s
#RegisterNumber:24001082
import numpy as np


A = np.array([[4,2],[2,4]])

# Compute the eigenvalues and eigenvectors
eigenvalues, eigenvectors = np.linalg.eig(A)

# Print the output in
print(f"Eigen values are {np.round(eigenvalues, 2)} and Eigen Vectors are {np.round(eigenvectors, 8)}")

```
## Output:

![Screenshot (1)](https://github.com/user-attachments/assets/0d1384f5-c332-4a4c-bc19-1565cec062a3)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
