# Read-from-CSV
## AIM:
To write a python program to read contents from a csv file
## ALGORITHM:
### Step 1:
import pandas as pd
### Step 2:
Using pd.read_csv method read the csv file .
### Step 3:
Using df.head print the first 10 rows of the csv file
### Step 4:
using df.tail() print the last 5 rows of the csv file
### Step 5:
using len(df.axes[]) print the total number of rows and columns with argument 0 for row and argument 1 for column
## PROGRAM:
```
import pandas as pd
f=pd.read_CSV('nba.csv')
print(f.head(10))
print(f.tail())
print('number of rows:',len(f.axes[0]))
print('number of columns:',len(f.axes[1]))
```
## OUTPUT:
![Screenshot 2024-01-02 215844](https://github.com/Harishragaventhira/Read-from-CSV/assets/145548269/91783b9b-b5e5-4fc8-abfa-7315bedf2daa)
![Screenshot 2024-01-02 220402](https://github.com/Harishragaventhira/Read-from-CSV/assets/145548269/5e00e60b-d938-4013-812d-ac921d83275a)
![Screenshot 2024-01-02 220427](https://github.com/Harishragaventhira/Read-from-CSV/assets/145548269/80af34a4-1f1a-4fe5-93ad-42064b16ea99)


## RESULT:
The output was verified sucessfully
