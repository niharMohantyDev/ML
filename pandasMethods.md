## Complete List of Pandas Methods

### DataFrame Methods:

1. **Creation**:
   - `pd.DataFrame()`: Create a new DataFrame.
   - `df.from_dict()`: Create a DataFrame from a dictionary.
   - `df.from_records()`: Create a DataFrame from a list of tuples or dictionaries.
   
2. **Viewing Data**:
   - `df.head()`: View the first n rows of the DataFrame.
   - `df.tail()`: View the last n rows of the DataFrame.
   - `df.info()`: Display a concise summary of the DataFrame.
   - `df.describe()`: Generate descriptive statistics of the DataFrame.
   
3. **Selection**:
   - `df[]` or `df.loc[]` or `df.iloc[]`: Select rows or columns.
   - `df.at[]` and `df.iat[]`: Access a single value for a row/column label pair.
   
4. **Manipulation**:
   - `df.drop()`: Drop specified labels from rows or columns.
   - `df.dropna()`: Remove missing values.
   - `df.fillna()`: Fill missing values.
   - `df.rename()`: Rename columns.
   - `df.sort_values()`: Sort by values.
   - `df.set_index()`: Set the DataFrame index.
   - `df.reset_index()`: Reset the index of the DataFrame.
   - `df.apply()`: Apply a function along an axis of the DataFrame.
   
5. **Operations**:
   - `df.groupby()`: Group DataFrame using a mapper or by a Series of columns.
   - `df.merge()`: Merge DataFrame or named Series objects with a database-style join.
   - `df.pivot_table()`: Create a spreadsheet-style pivot table.
   - `df.join()`: Join columns of another DataFrame.
   
6. **Statistics**:
   - `df.mean()`: Return the mean of the values for the requested axis.
   - `df.median()`: Return the median of the values for the requested axis.
   - `df.std()`: Return sample standard deviation over requested axis.
   
7. **Input/Output**:
   - `pd.read_csv()`, `pd.read_excel()`, `pd.read_sql()`, etc.: Read data from various file formats.
   - `df.to_csv()`, `df.to_excel()`, `df.to_sql()`, etc.: Write data to various file formats.
   - `df.to_dict()`: Convert DataFrame to dictionary.

8. **Indexing and Selecting Data**:
   - `df.loc[]`: Access a group of rows and columns by label(s) or a boolean array.
   - `df.iloc[]`: Access a group of rows and columns by integer position(s).
   - `df.at[]`: Access a single value for a row/column label pair.
   - `df.iat[]`: Access a single value for a row/column pair by integer position.

### Series Methods:

1. **Creation**:
   - `pd.Series()`: Create a new Series object.
   
2. **Viewing Data**:
   - `s.head()`, `s.tail()`, `s.info()`, `s.describe()`: Similar to DataFrame methods.
   
3. **Selection**:
   - `s[]` or `s.loc[]` or `s.iloc[]`: Select elements.
   
4. **Manipulation**:
   - `s.drop()`, `s.dropna()`, `s.fillna()`: Similar to DataFrame methods.
   - `s.rename()`: Rename the Series.
   - `s.sort_values()`: Sort the Series.
   - `s.unique()`, `s.value_counts()`: Find unique values or count occurrences of each value.
   
5. **Operations**:
   - `s.map()`: Apply a function to each element.
   - `s.apply()`: Apply a function along the axis of the Series.
   - `s.str`: String handling methods for Series with string data.
   
6. **Statistics**:
   - `s.mean()`, `s.median()`, `s.std()`: Similar to DataFrame methods.
   

