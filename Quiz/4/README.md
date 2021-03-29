### Quiz 4
1) A Loop is most like a Recursive function in the way it can run multiple statements¶
by itself in a single cell.
2) import numpy as np

def sortarray(x):
    for i in range(len(x)):
        swap = i + np.argmin(x[i:])
        (x[i], x[swap]) = (x[swap], x[i])
    return x
x = np.array([1,2,3,4,5,4,3,1])
sortarray(x)
##Working code for #2
array([1, 1, 2, 3, 3, 4, 4, 5])
