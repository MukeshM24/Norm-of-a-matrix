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
Python
### Register No: 26013543
### Developed By: Mukesh M
# 1-Norm of a Matrix
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### mat=np.array(eval(input()))
### ans=np.linalg.norm(mat,1)
### Norm_of_matrix="{:.2f}".format(ans)
### print(Norm_of_matrix)



# 2-Norm of a Matrix
'''
### Program to find 2-norm of a matrix.
### Developed by: Mukesh M
### RegisterNumber: 26013543
'''
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### mat=np.array(eval(input()))
### ans=np.linalg.norm(mat,2)
### Norm_of_matrix="{:.2f}".format(ans)
### print(Norm_of_matrix)



# Infinity Norm of a Matrix

### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### mat=np.array(eval(input()))
### ans=np.linalg.norm(mat,np.inf)
### print("{:2f}".format(ans))




## Output:
### 1-Norm of a Matrix
<br>
<img width="812" height="410" alt="image" src="https://github.com/user-attachments/assets/2ee3f515-83b2-4999-8466-d8f998432017" />

<br>
<img width="842" height="300" alt="image" src="https://github.com/user-attachments/assets/6ce40a6f-da0a-4940-9ff2-dec94878a8da" />

<br>

### 2-Norm of a Matrix
<br>
<img width="787" height="317" alt="image" src="https://github.com/user-attachments/assets/1bb6982f-cc21-4b66-ae2d-5653128efd69" />

<br>
<img width="865" height="342" alt="image" src="https://github.com/user-attachments/assets/d39b6ab5-6266-4e6c-8ce8-416f0e084f53" />

<br>

### Infinity Norm of a Matrix
<br>
<img width="820" height="341" alt="image" src="https://github.com/user-attachments/assets/45012f4f-9373-438e-9943-ed1149e59ea9" />

<br>
<img width="882" height="380" alt="image" src="https://github.com/user-attachments/assets/4e918702-1992-45ab-bf09-badd465546ad" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
