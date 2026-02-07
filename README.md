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
```Python
# Register No:212225240068
# Developed By:KARTHIC V
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_="{:.2f}".format(ans)
print(norm_)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_="{:.2f}".format(ans)
print(norm_)

```
## Output:
### 1-Norm of a Matrix
<img width="1244" height="624" alt="Screenshot 2026-02-07 093256" src="https://github.com/user-attachments/assets/7a87f2ef-7fad-413f-ac1a-ab5d4c5807da" />


### 2-Norm of a Matrix
<img width="1242" height="665" alt="Screenshot 2026-02-07 093306" src="https://github.com/user-attachments/assets/8394848e-de27-4f18-aa10-9af03d68bdf4" />


### Infinity Norm of a Matrix
<img width="1253" height="639" alt="Screenshot 2026-02-07 093319" src="https://github.com/user-attachments/assets/f14b4903-75d0-4acc-b585-e77e00d7f736" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
