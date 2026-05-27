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
# Register No:212225220061
# Developed By:mahith m
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
<img width="1422" height="866" alt="Screenshot 2026-05-27 090919" src="https://github.com/user-attachments/assets/3360c35b-5095-4582-94e1-d17db37d71d1" />

### 2-Norm of a Matrix
<img width="1475" height="883" alt="Screenshot 2026-05-27 090933" src="https://github.com/user-attachments/assets/02497ae3-8874-43ae-aacb-d0dba34b7355" />

### Infinity Norm of a Matrix
<img width="1386" height="744" alt="Screenshot 2026-05-27 090944" src="https://github.com/user-attachments/assets/5e64bfcd-d32e-44ea-b98b-2a305f45601e" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
