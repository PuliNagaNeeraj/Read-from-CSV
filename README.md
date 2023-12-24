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
# Developed by: Azeez Ahamad
# Register Number: 23003977
import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0))
print("NUmber of columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/AzeezBT/Read-from-CSV/assets/150319523/bfe36955-cd48-4b2e-ba5c-ef7d51ae0f0f)
![image](https://github.com/AzeezBT/Read-from-CSV/assets/150319523/f1249d41-8d6d-40f6-9bf8-6390600e1468)


## RESULT:
Thus the program is written to copy the contents from one file to another file
