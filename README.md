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
# Register No: 212224230077
# Developed By: Gokul Nath R

# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
<img width="966" height="961" alt="image" src="https://github.com/user-attachments/assets/caf8a393-77ac-4c51-9e9e-3598e074724a" />

### 2-Norm of a Matrix
<img width="893" height="1032" alt="image" src="https://github.com/user-attachments/assets/e68c032b-ac97-4b63-9032-6386117010fc" />

### Infinity Norm of a Matrix
<img width="872" height="921" alt="image" src="https://github.com/user-attachments/assets/7c8742a3-b6c0-422e-a12f-cd480ca552c7" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
