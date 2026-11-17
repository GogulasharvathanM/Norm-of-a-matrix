# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
### 1.	Hardware – PCs
### 2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
### Algorithm:
### 1. Start the program and get the matrix as input.
### 2. Calculate the maximum absolute column sum to find the 1-norm.
### 3. Calculate the maximum singular value to find the 2-norm.
### 4. Calculate the maximum absolute row sum to find the infinity-norm and display all results in two decimal places.
### Program:
```
 Register No: 26017320
 Developed By: Gogulasharvathan M
 1-Norm of a Matrix
Q.No.1
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat, 1)
print(f"{ans:.2f}")

Q.No.2
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat, 2)
print(round(ans, 2))

Q.No.3
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))





```
## Output:
### 1-Norm of a Matrix
<img width="1438" height="725" alt="{AC548A1B-1513-4B05-9A71-03AECE2D861E}" src="https://github.com/user-attachments/assets/e04243a7-de04-48a4-a228-9fcede5c0873" />

### 2-Norm of a Matrix
<img width="1454" height="858" alt="{188BEF6A-827F-46E4-AC9A-AC8ACEBBA045}" src="https://github.com/user-attachments/assets/113a7a6e-40d4-44f7-b9a6-10bc8fd92347" />

### Infinity Norm of a Matrix
<img width="1443" height="780" alt="{B41757FC-A6FB-4DF0-9CEF-4D0CEE324D9F}" src="https://github.com/user-attachments/assets/e535afbe-24b0-4a96-b869-88563bc9e802" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
