```python
# Import Numpy membuat perhitungan lebih ringan

import numpy as np
```


```python
# Checking Numpy Version

print(np.__version__)
```

    1.24.3
    


```python
# creating a numpy array

arr = np.array([1,2,3,4,5])
print(arr)
```

    [1 2 3 4 5]
    


```python
import numpy as np

arr = np.array([1,2,3,4,5])

print(arr)
print(type(arr))
```

    [1 2 3 4 5]
    <class 'numpy.ndarray'>
    


```python
#use a tuple to create a numpy array

import numpy as np

arr = np.array((1,2,3,4,5))

print(arr)
print(type(arr))
```

    [1 2 3 4 5]
    <class 'numpy.ndarray'>
    

Dimensions in arrays

A dimensions in arrays is one level or array dpth(nested arrays)


```python
# 0-D Arrays
```


```python
import numpy as np

arr = np.array(42)

print(arr)
```

    42
    


```python
# Create o 1-D array

import numpy as np

arr = np.array([1,2,3,4,5])

print(arr)
```

    [1 2 3 4 5]
    

#create o 2-D containing two arrays


```python
import numpy as np

arr = np.array([[1,2,3], [4,5,6], [7,8,9]])

print(arr)
```

    [[1 2 3]
     [4 5 6]
     [7 8 9]]
    

#create o 3-D with 2-D array, both contoining two arrays


```python
import numpy as np

arr = np.array([[[1,2,3], [4,5,6]],[[1,2,3], [4,5,6]]])

print(arr)
```

    [[[1 2 3]
      [4 5 6]]
    
     [[1 2 3]
      [4 5 6]]]
    


```python
# check how many dimensions the array have

import numpy as np

a = np.array(42)
b = np.array([1,2,3,4,5])
c = np.array([[1,2,3], [4,5,6]])
d = np.array([[[1,2,3],[4,5,6]],[[1,2,3], [4,5,6]]])

print(a.ndim)
print(b.ndim)
print(c.ndim)
print(d.ndim)
```

    0
    1
    2
    3
    

# create on array with 5 dimension and verify that it has 5 dimensions (cara lain untuk membuat array)


```python
import numpy as np

arr = np.array([1,2,3,4], ndmin=5)

print(arr)
print('number of dimensions :', arr.ndim)
```

    [[[[[1 2 3 4]]]]]
    number of dimensions : 5
    

# get the first element from the following array


```python
import numpy as np

arr = np.array([1,2,3,4])

print(arr[1])
```

    2
    

# get third and fourth element from the following array and add them


```python
import numpy as np

arr = np.array([1, 2, 3, 4])

print(arr[2] + arr[3])
```

    7
    

# access the element on the first row,second column


```python
import numpy as np

arr = np.array([[1,2,3,4,5],[6,7,8,9,10]])

print('2nd elemnt on list row: ', arr[0,1])
```

    2nd elemnt on list row:  2
    

# accses the third element of the second of the first array


```python
import numpy as np

arr = np.array([[[1,2,3],[4,5,6]], [[7,8,9], [10,11,12]]])

print(arr[1,0,2])
```

    9
    

TASK1 - HARI SENIN


```python
#task import numpy

import numpy as np
```


```python
#checking version numpy

print(np.__version__)
```

    1.24.3
    


```python
matrix = np.array([[1,3,4], [2,4,5], [8,6,9]])
print(matrix)
```

    [[1 3 4]
     [2 4 5]
     [8 6 9]]
    

TASK2- HARI SENIN


```python
# 0-D Array

import numpy as np

arr = np.array(5)

print(arr)
```

    5
    


```python
# 1-D Array

arr = np.array([1,2,3,4,5,6])

print(arr)
```

    [1 2 3 4 5 6]
    


```python
arr = np.array([[1,4,6], [7,8,9]])

print(arr)
```

    [[1 4 6]
     [7 8 9]]
    


```python

```
