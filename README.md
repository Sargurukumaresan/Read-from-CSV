# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:

Import the pandas function as pd.
### Step 2:

Read the file and store it in the variable f.
### Step 3:

Print the head and tail.
### Step 4:

Print the number of rows using the length function(len).
### Step 5:

Print the number of coloumns using the same length function(len).

## PROGRAM:
```
Developed by : SARGURU K
REF NO : 22002828

import pandas as pd
f=pd.read_csv('cars.csv')
print(f.head(10))
print(f.tail())
print("Row:",len(f.axes[0]))
print("Col:",len(f.axes[1]))
```

## OUTPUT:
![1](./OUT%201.png)



## RESULT:
Thus the program is successfully executed.
