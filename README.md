# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.
## ALGORITHM:
Step 1:
Import pandas as pd.

Step 2:
Read the CSV file using read_csv method.

Step 3:
Use head and tail method to get the required contents from the file.

Step 4:
Use len() method to get the number of rows and columns

Step 5:
Print the output.

## PROGRAM:
```
import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("rows",df.axes[0])
print("columns",df.axes[1])
print("no of rows",len(df.axes[0]))
print("no of columns",len(df.axes[1]))
```

## OUTPUT:

<img width="614" alt="Screenshot_20230610_115758" src="https://github.com/PERARASU10/Read-from-CSV/assets/118348589/88196f03-583d-498e-a060-2530e3a044a9">


<img width="552" alt="Screenshot_20230610_115554" src="https://github.com/PERARASU10/Read-from-CSV/assets/118348589/eb5bc7ed-55dd-471e-9293-f0b9b055c5e0">

<img width="567" alt="Screenshot_20230610_115653" src="https://github.com/PERARASU10/Read-from-CSV/assets/118348589/04674536-db94-4090-b5a6-c785d3a28863">


## RESULT:
Thus a python program is written to read the contents of a CSV file.
