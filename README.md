**Function / Method**   | **Description / Use**                                                     |
| ----------------------- | ------------------------------------------------------------------------- |
| `pd.Series()`           | Create a 1D labeled array, fundamental Pandas data structure              |
| `pd.DataFrame()`        | Create a 2D labeled tabular data structure                                |
| `pd.read_csv()`         | Load data from a CSV file                                                 |
| `pd.read_json()`        | Load data from a JSON file                                                |
| `pd.read_excel()`       | Load data from Excel files                                                |
| `df.to_csv()`           | Save DataFrame to CSV file                                                |
| `df.to_excel()`         | Save DataFrame to Excel file                                              |
| `df.head()`             | View the first n rows (default 5)                                         |
| `df.tail()`             | View the last n rows                                                      |
| `df.info()`             | Summary of DataFrame, including data types, non-null counts, memory usage |
| `df.describe()`         | Statistical summary (mean, std, quartiles) of numeric columns             |
| `df.shape`              | Get number of rows and columns                                            |
| `df.columns`            | Get list of column names                                                  |
| `df.dtypes`             | Data types of each column                                                 |
| `df['col']`             | Select single column (returns Series)                                     |
| `df[['col1', 'col2']]`  | Select multiple columns (returns DataFrame)                               |
| `df.loc[]`              | Label-based row and column selection                                      |
| `df.iloc[]`             | Integer position-based row and column selection                           |
| `df[df['col'] > value]` | Boolean indexing / filtering rows based on conditions                     |
| `df.isnull()`           | Detect missing values                                                     |
| `df.dropna()`           | Drop rows with missing values                                             |
| `df.fillna(value)`      | Fill missing values with a specified value                                |
| `df.rename(columns={})` | Rename columns                                                            |
| `df.astype()`           | Change data type of columns                                               |
| `df.assign()`           | Add or modify columns using functions                                     |
| `df.groupby()`          | Group data by one or more columns for aggregation                         |
| `df.agg()`              | Aggregate grouped data using functions like mean, sum, min, max           |
| `pd.concat()`           | Concatenate DataFrames vertically or horizontally                         |
| `pd.merge()`            | SQL-style join/merge of DataFrames                                        |
| `df.sort_values()`      | Sort DataFrame by column(s)                                               |
| `df.rank()`             | Rank data within columns                                                  |
| `pd.to_datetime()`      | Convert strings or numbers to datetime type                               |
| `df.set_index()`        | Set a column as index                                                     |
| `df.reset_index()`      | Reset index to default integer index                                      |
| `df.resample()`         | Resample time series data to different frequencies (e.g., monthly)        |
| `df.rolling()`          | Compute rolling/window calculations                                       |
| `df.apply()`            | Apply a function across rows or columns                                   |
| `df.pipe()`             | Chain multiple transformations cleanly                                    |
| `df.sample()`           | Randomly sample rows                                                      |
| `df.drop_duplicates()`  | Remove duplicate rows                                                     |
| `df.memory_usage()`     | Show memory usage of DataFrame columns                                    |
| `df.query()`            | Query DataFrame using a string expression (SQL-like syntax)               |
