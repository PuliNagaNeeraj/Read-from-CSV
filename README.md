# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.
## ALGORITHM:
### Step 1:
Import pandas as pd.

### Step 2:
Read the CSV file using read_csv method.

### Step 3:
Use head and tail method to get the required contents from the file.

### Step 4:
Use len() method to get the number of rows and columns.

### Step 5:
Print the output

## PROGRAM:
```
### Developed by: PULI NAGA NEERAJ
### Register Number: 23004033
import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0))
print("NUmber of columns:",len(df.axes[1]))
```
## OUTPUT:
![Screenshot 2023-12-24 154825](https://github.com/PuliNagaNeeraj/Read-from-CSV/assets/138849173/0a4574f2-6152-4dcd-a52a-98fe896a2b82)
![Screenshot 2023-12-24 154856](https://github.com/PuliNagaNeeraj/Read-from-CSV/assets/138849173/7a7b4044-e66e-4d67-b827-af3f60d783c0)

## RESULT:
Thus python program for reading content from a CSV file is successful.


