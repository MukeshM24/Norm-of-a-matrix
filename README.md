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
# Register No: 26013543
# Developed By: Mukesh M
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:2f}".format(ans))




```
## Output:
### 1-Norm of a Matrix
<br>
<img width="527" height="245" alt="image" src="https://github.com/user-attachments/assets/e690515f-f0ac-41be-8fad-6258d93de04e" />

<br>
<img width="778" height="287" alt="image" src="https://github.com/user-attachments/assets/a647904d-e3d5-4ad3-96c1-53335d2a630c" />

<br>

### 2-Norm of a Matrix
<br>
<img width="690" height="295" alt="image" src="https://github.com/user-attachments/assets/c96463a3-dc22-4520-a740-a2094843f9b1" />

<br>
<img width="520" height="322" alt="image" src="https://github.com/user-attachments/assets/857332d5-7690-44c6-90af-bea1f70ae854" />

<br>

### Infinity Norm of a Matrix
<br>
<img width="408" height="205" alt="image" src="https://github.com/user-attachments/assets/e7ecd344-54e3-41d5-b458-c4d53f950367" />

<br>
<img width="581" height="277" alt="image" src="https://github.com/user-attachments/assets/f6e8dc58-0b1d-4d71-b44b-207f2cfa25b5" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
