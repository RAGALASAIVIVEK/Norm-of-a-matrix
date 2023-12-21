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
# Register No:23003676
# Developed By:sai vivek ragala
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))
# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Ragala Sai Vivek
RegisterNumber: 23003676
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))
# Infinity Norm of a Matrix
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-21 180152](https://github.com/RAGALASAIVIVEK/Norm-of-a-matrix/assets/144979718/2e38cb7d-114d-49b9-8d9c-a19ac557de55)

### 2-Norm of a Matrix
![Screenshot 2023-12-21 180358](https://github.com/RAGALASAIVIVEK/Norm-of-a-matrix/assets/144979718/251ab0ea-0d52-4113-89b7-9492d6fd2e56)

### Infinity Norm of a Matrix
![Screenshot 2023-12-21 180448](https://github.com/RAGALASAIVIVEK/Norm-of-a-matrix/assets/144979718/877fe0cd-10c8-4706-9242-66582e452cb7)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
