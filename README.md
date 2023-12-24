# Read-from-CSV

## AIM:

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
# Developed by: Kavinraja D
# Register Number: 22007928
import pandas as pd
df = pd.read_csv('pandascsv.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![Screenshot 2023-12-24 095002](https://github.com/2005Mukesh/Read-from-CSV/assets/138849308/154e533c-1e64-4c6a-918d-fb586b585f0b)
## RESULT:
Thus the program is written to copy the contents from one file to another file
