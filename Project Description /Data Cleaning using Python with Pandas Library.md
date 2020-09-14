# Extra Reading - Data Cleaning using Python with Pandas Library 
## Step 1: Import the required libraries 
```
import pandas as pd
import numpy as np
import csv 
```

## Step 2: Getting the data
```
df = pd.read_csv("datafile.csv")
df.head(5)
```

## Step 3: Removing the unused or irrelevant columns 
```
to_drop = ['a',
			'b',
			'c']
df.drop(to_drop, inplace = True, axis = 1) 
df.head(5)
```

## Step 4: Renaming the column names
```
new_name = {'age': 'Age', 
			  'sex': 'Sex',
			  'chol': 'Cholesteror'}
df.rename(columns = new_name, inplace = True)
df.head()
```

## Step 5: Replacing the values of rows 
```
replace_values = {0:'F', 1:'M'}
df = df.replace({"Sex": replace_values})
df.head()
```

## Reference 
[Data Cleaning using Python with Pandas Library. | by Tanu N Prabhu | Towards Data Science](https://towardsdatascience.com/data-cleaning-with-python-using-pandas-library-c6f4a68ea8eb), *Tanu N Prabhu, Data Cleaning using Python Pandas Library. Medium, 2019*