# Data Analytic: Week 1


## Data Manipulation 

### Aggregate data 
In the world of pandas DataFrames, data aggregation involves summarizing and combining data points to create a more concise and informative representation.

#### 1. Pivoting
Pivoting involves restructuring data from a format where each observation has multiple rows (long format) to a format where summary statistics for different categories are displayed in columns (wide format). This transformation makes it possible to condense large data sets and highlight important insights more effectively.
Example :
![image](https://github.com/Rnovranza/Python_Week_3/assets/165742717/a108192c-60b3-463a-9769-f379dcee7a09)


#### 2. Grouping
Grouping is a fundamental operation in pandas that allows organizing and analyzing data based on shared characteristics. This involves segmenting the DataFrame rows into different groups based on the values in one or more columns.
Example :

![image](https://github.com/Rnovranza/Python_Week_3/assets/165742717/6035a3a5-a73b-422e-ac00-5e37c5de3516)


#### 3. Crosstab
Crosstab is a data aggregation technique that summarizes data from a long format (multiple rows per observation) into a more concise and informative wide format (summary statistics displayed in rows and columns). It is a valuable tool for data exploration and analysis, particularly when dealing with categorical data.
Example :

![image](https://github.com/Rnovranza/Python_Week_3/assets/165742717/e28b8ef3-3b3e-4f07-adf3-9dae00b46faf)


#### 4. Concatenation
Concatenation (Concat) combines DataFrames along a specific axis (0 for rows, 1 for columns). It stacks DataFrames on top of each other (axis 0) or side-by-side (axis 1) to create a larger DataFrame.
Example :

![image](https://github.com/Rnovranza/Python_Week_3/assets/165742717/7b340acb-202c-4346-bfcd-01c043458aa1)


#### 5. Merging
Merging combines data from two separate DataFrames based on a common column or index. It allows to create a new DataFrame that includes columns from both original DataFrames while establishing a specific relationship between the corresponding rows.
Example :

![image](https://github.com/Rnovranza/Python_Week_3/assets/165742717/1257a0c0-ed4f-4847-bb0e-0b304c3ecace)


### Organize data
Data organization refers to the process of structuring and arranging data within pandas DataFrames to facilitate analysis and interpretation.

#### 1. Sorting
In the context of organized data, particularly within pandas DataFrames, Sorting refers to the process of rearranging rows based on the values in one or more columns. The goal is to create a specific order that facilitates data exploration, analysis, and interpretation.
Example :

![image](https://github.com/Rnovranza/Python_Week_3/assets/165742717/2fa8afd2-6d08-43cf-948c-c1687873a371)


#### 2. Get dummies
The get_dummies function from the pandas library performs one-hot encoding on categorical data. It takes a DataFrame with categorical columns and returns a new DataFrame with new binary columns representing each unique category.
Example :

![image](https://github.com/Rnovranza/Python_Week_3/assets/165742717/b4364b7e-ad8d-4f90-94d3-b0bc4a5ed796)


#### 3. Renaming
Renaming columns or rows in a pandas DataFrame is considered a data organization technique. It falls under the category of data wrangling, which involves cleaning, transforming, and preparing data for analysis. Renaming helps you create more meaningful and descriptive column and row names, making it easier to understand and interpret your data.
Example :

![image](https://github.com/Rnovranza/Python_Week_3/assets/165742717/f7f97bfa-07d7-424a-80dd-2d5e72360915)
