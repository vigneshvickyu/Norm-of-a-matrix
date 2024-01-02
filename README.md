# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```Python
# Register No:
# Developed By:
# 1-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by:VIGNESH M
RegisterNumber: 23014020
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: VIGNESH M
RegisterNumber: 23014020
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: VIGNESH M
RegisterNumber: 23014020
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
```![image](https://github.com/vigneshvickyu/Norm-of-a-matrix/assets/151948835/8e62b497-5965-43d2-becf-0b8681164b1d)


### 2-Norm of a Matrix
```![image](https://github.com/vigneshvickyu/Norm-of-a-matrix/assets/151948835/e9ab2885-66b3-446d-bd39-439423ae4fd9)


### Infinity Norm of a Matrix
``![image](https://github.com/vigneshvickyu/Norm-of-a-matrix/assets/151948835/75695bf1-8f3b-4a26-ad48-d747e735af95)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
