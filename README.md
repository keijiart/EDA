# Exploratory Data Analysis (EDA)

## What is EDA?

EDA is nothing but a data exploration technique to understand various aspects of the data.

## What is the aim of EDA

It is basically used to filter the data from redundancies: clean the data.

Understar the relation between variables.

## Steps of EDA

1. Understand the data: number of columns, rows, variables.
2. Clean the data: remove noise data.
3. Analyses the relation between variables.

## Basic functions in EDA

- `pd.data_csv('database.csv')`

- `database.head()`
  
- `database.shape()`
  - Number of columns and rows
  
- `database.info()`
  - Look at the data types of each column

- `database.isnull().sum()`
  - Check for missing (null) values in all of the columns

- `database.describe()`
  - Perform summary statistics

- `database['column1', 'column2', 'column3'] = database['column1', 'column2', 'column3'].replace(0, np.NaN)`
  - Replace the instances of `0` with `NaN`

- `database[['column1']] = database[['column']].replace('O', 0)`
  - Replace the any instance of `O` with `0`

- `database['column1'] = database['column1'].astype('int64')`
  - Change the type of variable: `object`, `int64`, `float64`

- `database['columnN'].unique()`
  - Print unique values of N column
  - CDB







