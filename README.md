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
```
#program to read the nba file
#Developed by:R.SANJANA
#Register Number: 23008112

import pandas as pd
df= pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column",len(df.axes[0]))
print("rows",len(df.axes[1]))
```

## OUTPUT
![Screenshot 2023-12-26 091128](https://github.com/23008112/Read-from-CSV/assets/138972470/4102350d-f7e6-4919-9aec-4586538717b2)

## RESULT:
Thus the program is written to read the csv file.
