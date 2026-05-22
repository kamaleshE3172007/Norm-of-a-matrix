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
# Register No:212225230122
# Developed By:KAMALESH E

# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=eval(input())
b=np.linalg.norm(a,1)
print(f"{b:.2f}")


# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=eval(input())
b=np.linalg.norm(a,2)
print(f"{b:.2f}")

# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=eval(input())
b=np.linalg.norm(a,np.inf)
print(f"{b:.2f}")



```
## Output:
### 1-Norm of a Matrix
<img width="1237" height="342" alt="image" src="https://github.com/user-attachments/assets/f3d00d5d-9522-47b6-a7d7-c9f7224086c0" />


### 2-Norm of a Matrix
<img width="1247" height="376" alt="image" src="https://github.com/user-attachments/assets/2b36d286-e5bf-4b53-8fa8-3ede30435bdf" />


### Infinity Norm of a Matrix
<img width="1245" height="421" alt="image" src="https://github.com/user-attachments/assets/ec0ddced-6e5c-43a5-90e8-3d4e842692d5" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
