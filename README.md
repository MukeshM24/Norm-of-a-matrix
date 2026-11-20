### Norm of a matrix
### Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
### Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
### Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
### Program:
```Python
'''
 Register No:26013543
 Developed By:Mukesh M
'''
1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




### 2-Norm of a Matrix

'''
Developed by: Mukesh M
RegisterNumber: 26013543
'''
program to find 2-norm of matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



###  3-Infinity Norm of a Matrix

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
<img width="795" height="477" alt="image" src="https://github.com/user-attachments/assets/f677ac15-568d-4d2a-adda-194ca503c17e" />

<br>
<img width="862" height="315" alt="image" src="https://github.com/user-attachments/assets/ea16878f-2daf-40a3-b671-125a21e8c5f6" />

<br>

### 2-Norm of a Matrix
<br>
<img width="837" height="408" alt="image" src="https://github.com/user-attachments/assets/28f8425b-0d8b-4c08-8ded-dc44443c212c" />

<br>
<img width="792" height="352" alt="image" src="https://github.com/user-attachments/assets/bee6075a-bff2-467a-9fe7-35a18bf808ab" />

<br>

### Infinity Norm of a Matrix
<br>
<img width="796" height="466" alt="image" src="https://github.com/user-attachments/assets/7f279eba-5a34-4e1d-b268-40fa3f329551" />

<br>
<img width="855" height="325" alt="image" src="https://github.com/user-attachments/assets/31c3afdb-53ea-41c8-82c5-0087b218ebf8" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
