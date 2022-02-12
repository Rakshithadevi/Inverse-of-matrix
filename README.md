# Inverse-of-matrix

## AIM:
To write a program to perform selection sort and insertion sort using python programming.

## ALGORITHM:
```
Step 1:
Import Numpy module as np.
 Step 2:
Create empty lists.
 Step 3:
Get input from the user for number of rows and columns.
 Step 4:
Use nested lists to append list.
#Step 5:
Print the inverse of the array using np.linalg.inv
```
## PROGRAM:
import numpy as np
l1,l2=[],[]
n1,n2=int(input()),int(input())
for i in range(n1):
    for j in range(n2):
        values=int(input())
        l1.append(values)
    l2.append(l1)
    l1=[]
print(l2)
a=np.linalg.inv(l2)
print(a)

## OUTPUT:
![image](https://user-images.githubusercontent.com/94165326/153698584-4701455c-9f3a-483b-984e-1c9ad69a3bd2.png)




## RESULT:
Thus the program is written to perform inverse of matrix using python programming.
