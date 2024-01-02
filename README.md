# Read-from-CSV

## AIM:
To read from CSV

## ALGORITHM:
### Step 1:
Import pandas as pd.

### Step 2:
Read the CSV file using read_csv method.

### Step 3:
Use head and tail method to get the required contents from the file.

### Step 4:
Use len() method to get the number of rows and columns

### Step 5:
Print the output:

## PROGRAM:
```
#Program to read a file from csv
#Developed by: MS Dharanish
#Register number:212223240027
import pandas as pd
f=pd.read_csv("nba.csv")
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
```

## OUTPUT:
![Screenshot 2024-01-02 142752](https://github.com/MSDharanish-23011819/Read-from-CSV/assets/147139454/fbaa9203-8bc8-43c4-8d86-7157314417ac)

## RESULT:
Thus a python program to read the contents of a CSV file has been executed successfully.

