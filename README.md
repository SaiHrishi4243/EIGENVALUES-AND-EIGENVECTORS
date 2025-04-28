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

```python

#Program to find the eigen values and eigen vectors.
#Developed by: Sai Hrishi M
#RegisterNumber: 212224240140

import numpy as ma
a=ma.array([[2,-3,0],[2,-5,0],[0,0,3]])
Eig_val,Eig_vec=ma.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(Eig_val,Eig_vec))

```

## Output:

![Screenshot 2025-04-29 002151](https://github.com/user-attachments/assets/8572167a-7af0-447a-9a90-637cfb6a6212)

![Screenshot 2025-04-29 002223](https://github.com/user-attachments/assets/a6c00941-64c9-4d85-bb55-d54bca29717d)

## Result:

Thus the Eigenvalue and Eigenvector is successfully solved using python program
