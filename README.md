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
# Register No:25018432
# Developed By:Saadhana A
# 1-Norm of a Matrix
'''
program to find 1-norm of a matrix
developed by : Saadhana A
register number : 25018432
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:2f}",format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
'''
program to find 2-norm of a matrix
developed by : Saadhana A
register number : 25018432
'''
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,2)
n=f"{a:2f}"
print(n)

# Infinity Norm of a Matrix
'''
program to find infinity norm of a matrix
developed by : Saadhana A
register number : 25018432
'''
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,np.inf)
n=f"{a:2f}"
print(n)

## Output:
### 1-Norm of a Matrix
<br>
<img width="953" height="268" alt="Screenshot 2025-10-27 at 9 03 43 PM" src="https://github.com/user-attachments/assets/6ed06bab-190b-4014-9bdf-19f012b071a8" />
<br>
<br>

### 2-Norm of a Matrix
<br>
<img width="951" height="299" alt="Screenshot 2025-10-27 at 9 04 01 PM" src="https://github.com/user-attachments/assets/e2596ebb-b3eb-4fbc-b736-117d46aba03a" />
<br>
<br>

### Infinity Norm of a Matrix
<br>
<img width="950" height="273" alt="Screenshot 2025-10-27 at 9 04 25 PM" src="https://github.com/user-attachments/assets/dba92306-5182-4f05-978f-cd3dc4d137b3" />
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
