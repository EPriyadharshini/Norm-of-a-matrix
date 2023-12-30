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
# Register No:23012593
# Developed By:PRIYADHARSHINI.E
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: PRIYADHARSHINI.E
RegisterNumber:23012593 
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)



# 3-Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
<img width="276" alt="image" src="https://github.com/EPriyadharshini/Norm-of-a-matrix/assets/144870831/5137a5dd-bc9a-4171-9365-b444515663e3">


### 2-Norm of a Matrix
<img width="267" alt="image" src="https://github.com/EPriyadharshini/Norm-of-a-matrix/assets/144870831/d651a612-5664-4c4d-a5d9-6d46919bf47b">


### 3-Infinity Norm of a Matrix
<img width="258" alt="image" src="https://github.com/EPriyadharshini/Norm-of-a-matrix/assets/144870831/6868f068-cf32-4480-badb-481a378ff5ae">


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
