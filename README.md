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
# Register No:212224240038
# Developed By:DINESH S
# 1-Norm of a Matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print(result)
```

# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: KISHOR K R
RegisterNumber: 212224110032
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print(f"{result:.2f}")
```
# Infinity Norm of a Matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
print(f"{result:.2f}")
```
## Output:
### 1-Norm of a Matrix

<img width="873" height="827" alt="image" src="https://github.com/user-attachments/assets/cf727e14-31e6-452a-a1d1-4be45f91a506" />

### 2-Norm of a Matrix

<img width="898" height="880" alt="image" src="https://github.com/user-attachments/assets/ee68b5b4-f040-43e9-af3e-9a77a9c8d3d3" />

### Infinity Norm of a Matrix

<img width="800" height="780" alt="image" src="https://github.com/user-attachments/assets/ed0bdc59-ffb9-4126-ba1c-7dc0c4684423" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
