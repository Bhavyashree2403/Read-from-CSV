# Read-from-CSV

## AIM:
To write a python program for reading the csv file content
## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.

### Step 2:
Print the number of contents to be displayed using df.head().

### Step 3:
The number of rows returned is defined in Pandas option settings.

### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
Developed by:Bhavyashree R
Register number: 212223110006
```
import pandas as pd
df=pd.read_csv("NBA.csv")
print(df.head(10))
print(df.tail())
print("No of rows",len(df.axes[0]))
print("No of coloumn",len(df.axes[1]))
```

## OUTPUT:
![alt text](<Screenshot 2024-05-14 062246.png>)
![alt text](<Screenshot 2024-05-14 062255.png>)
## RESULT:
Thus the program is written to read the csv file.