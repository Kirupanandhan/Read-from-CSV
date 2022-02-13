# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file
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
Print the output.
## PROGRAM:
```
Developed by:  Shavedha Y
Register Number: 21500429

import pandas as pd
df = pd.read_csv('data1.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![csv](https://user-images.githubusercontent.com/94386222/153755864-49999a79-beed-422a-9aba-a1f69f97fa94.png)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
