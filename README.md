# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm for 1 norm matrix:
```
1. Get the input matrix using np.array()
2. Find the 1-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
```
## Algorithm for 2 norm matrix:
```
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
```
## Algorithm for infinity norm matrix:
```
1. Get the input matrix using np.array()   
2. Find the Infinity norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
```
## Program:
```Python
# Register No:24006268
# Developed By:shravani.m
# 1-Norm of a Matrix


import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,1)
print(result)




# 2-Norm of a Matrix

import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,2)
norm_matrix="{:.2f}".format(result)
print(norm_matrix)




# Infinity Norm of a Matrix

import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,np.inf)
print(result)

```
## Output:
### 1-Norm of a Matrix
<br>![Screenshot 2024-12-12 184012](https://github.com/user-attachments/assets/f2021144-0033-4d99-86ee-d18e1766df0d)

<br>
<br>

### 2-Norm of a Matrix
<br>![Screenshot 2024-12-12 184410](https://github.com/user-attachments/assets/62a35616-b931-408a-b4d2-80670526b8db)

<br>
<br>

### Infinity Norm of a Matrix
<br>![Screenshot 2024-12-12 184423](https://github.com/user-attachments/assets/e47afd4a-95cc-4bbc-9fce-6212bc447bbd)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
