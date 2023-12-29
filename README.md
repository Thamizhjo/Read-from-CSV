## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_CSV method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Display the result.

## PROGRAM:
```
Developed by: Thamizh Kumaran
RegisterNumber: 23004070
To write a python program for reading content from a CSV file.
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:
<img width="644" alt="292658958-930f2610-3e9b-4fa5-a8af-d555b2f3f40c" src="https://github.com/Thamizhjo/Read-from-CSV/assets/123891476/770e34b9-76b9-4ef4-8190-1f11f5582a5a">


## RESULT:
Thus the Python program for reading content from a CSV file.

