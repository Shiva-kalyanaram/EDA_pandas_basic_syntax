# EDA_pandas_basic_syntax

# Pandas for Data Exploration in Python

[Pandas](https://pandas.pydata.org/) is a powerful Python library for data manipulation and analysis. This guide covers fundamental operations to help you explore and understand your dataset.

## Basic Operations

### 1. Import Pandas
```python
import pandas as pd

df = pd.read_csv('your_data.csv')

# Display the first few rows
print(df.head())

# Get summary statistics
print(df.describe())

# Display data types and missing values
print(df.info())


# Select a single column
column_data = df['Column_Name']

# Select multiple columns
subset = df[['Column1', 'Column2']]

# Check for missing values
print(df.isnull().sum())

# Drop rows with missing values
df_cleaned = df.dropna()

# Fill missing values with a specific value
df_filled = df.fillna(value)

# Check for missing values
print(df.isnull().sum())

# Drop rows with missing values
df_cleaned = df.dropna()

# Fill missing values with a specific value
df_filled = df.fillna(value)

