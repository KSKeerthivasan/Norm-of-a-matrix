# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
Program to find norms of a matrix.

Developed by: Keerthvasaan KS

RegisterNumber: 24900276 

# 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
# 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
# Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-01 165215](https://github.com/user-attachments/assets/c72ee287-12f8-490d-87c0-1e2a6d123bf0)
<br>

### 2-Norm of a Matrix
<br>![Screenshot 2024-12-01 165232](https://github.com/user-attachments/assets/213a1927-45d3-4d2f-a2e0-0a7e784ec1f2)
<br>

### Infinity Norm of a Matrix
<br>![Screenshot 2024-12-01 165247](https://github.com/user-attachments/assets/0eed31b6-9f8b-4780-9896-5651dfe5a368)
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
