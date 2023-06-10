# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file
## ALGORITHM:
Step 1:
Import pandas as pd.

Step 2:
Read the CSV file using read_csv method.

Step 3:
Use head and tail method to get the required contents from the file.

Step 4:
Use len() method to get the number of rows and columns.

Step 5:
Print the output

## PROGRAM:
```
#gokularamanan .k
#ref no:212222230040
import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("rows",df.axes[0])
print("columns",df.axes[1])
print("no of rows",len(df.axes[0]))
print("columns",len(df.axes[1]))
```
## OUTPUT:
![Screenshot (119)](https://github.com/Gokulanbazhagan/Read-from-CSV/assets/119518996/5a2e894f-7390-41b4-bb2e-1acfea0fe0b5)

## RESULT:
Thus the program is written to copy the contents from one file to another file
