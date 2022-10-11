# Read-from-CSV

## AIM:
 To read and proccess the csv file

## ALGORITHM:
### Step 1:import pandas as pd
### Step 2:open the file in read mode
### Step 3:print the first 9 and the tail
### Step 4:print the rows
### Step 5:print the columns

## PROGRAM:
```python
#developed by: Naveenaa A.K
#reference no: 22003091
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))
```

## OUTPUT:
![CSV](https://user-images.githubusercontent.com/113497406/195033879-9e03f32d-07fd-4b9b-b1d8-426ecbfa69cc.png)

## RESULT:
hence the programe is executed successfully!
