## DATE:
## EXNO 07: Norm of a matrix
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

### Register No:212223230068
### Developed By:HAREESH R
## 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)
```


## 2-Norm of a Matrix
```
import numpy as np
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)
```



## Infinity Norm of a Matrix

```

import numpy as np
mat=np.array(eval(input()))

norm=np.linalg.norm(mat,ord=np.inf)
print("{:.2f}".format(norm))

```
## Output:
### 1-Norm of a Matrix

![Screenshot 2024-10-20 181939](https://github.com/user-attachments/assets/d85e94ea-c035-4a90-b883-8213e2ba743d)

### 2-Norm of a Matrix

![Screenshot 2024-10-20 182015](https://github.com/user-attachments/assets/3e952854-75d8-446b-b638-c3f8d3a1d372)

### Infinity Norm of a Matrix

![Screenshot 2024-10-20 182046](https://github.com/user-attachments/assets/42b81013-ac80-4686-a43b-fad938655ecd)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
