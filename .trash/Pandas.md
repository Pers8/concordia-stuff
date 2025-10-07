# 🐼 Pandas
#pandas

[[Dashboard]] > [[Pandas]]

---

## Overview

Pandas is ==a Python library used for working with data sets.== 
It provides functions for analyzing, cleaning, exploring, and manipulating data.  
It was created by ==Wes McKinney== in ==2008==.  
The name "Pandas" refers to ==Panel Data== and ==Python Data Analysis==.

---

## Why Use Pandas?

Why is Pandas important in data science?::Because it allows us to work with large datasets, clean them, and extract insights using statistical methods.

---

Pandas can clean messy data sets and make them readable and relevant.  
==Relevant data== is essential in ==data science==.

---

## Core Benefits

What can Pandas do?
?
- Identify correlations between columns  
- Compute statistical summaries (mean, max, min)  
- Delete rows that are irrelevant or contain NULL values  
- Prepare data for machine learning or reporting

---

## DataFrames in Pandas

What is a DataFrame in Pandas?::A two-dimensional, tabular data structure with labeled axes (rows and columns), similar to a table in SQL or Excel.

How do you create a simple DataFrame from a dictionary?
?
```python
import pandas

mydataset = {
  'cars': ["BMW", "Volvo", "Ford"],
  'passings': [3, 7, 2]
}

myvar = pandas.DataFrame(mydataset)

print(myvar)
```

What does this code output (the one with `cars` and `passing`)?  
?
```markdown
    cars  passings
0    BMW         3
1  Volvo         7
2   Ford         2
```

---

## Series in Pandas

What is a Pandas Series?::A one-dimensional array-like object that can hold data of any type (like a single column from a table).

What labels does a Series use if none are specified?::The values are labeled with their index number: 0, 1, 2, etc.

How can you access a value in a Series?::By using its label (index) — either the default index or one you assign yourself.

How can you define custom labels in a Series?
?
Use the `index` argument while creating the Series to set custom labels.  
Once set, you can access values using those labels.

How can you use a dictionary to create a Series?::By passing a dictionary as the data — the **keys become the labels**, and the **values become the data**.

How do you include only specific items from a dictionary in a Series?
?
Use the `index` argument to specify a subset of keys you want to include in the Series.

---

## Related Concepts

What is Data Science?::A branch of computer science where we study how to store, use, and analyze data to extract insights.

What is GitHub?::A platform that enables many people to work collaboratively on the same codebase.

---
