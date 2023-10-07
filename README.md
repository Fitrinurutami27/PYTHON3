# PYTHON3
In week 3 we learn about numpy and pandas as the last week of learning about python

# The Numpy Method
The Numpy method is a very popular library in the Python programming language which is used for numerical computations. So Numpy makes Python calculations light.
## Functions of numpy methods:
1. Multidimensional Arrays: NumPy allows you to create and manage efficient multidimensional arrays. It helps in representing data like matrices, vectors, and other numerical data sets.
2. Mathematical Operations: NumPy provides various mathematical and linear algebra operations such as addition, subtraction, multiplication, and division between arrays. This makes processing numerical data easier.
3. Indexes and Slicing: You can easily access the elements in a NumPy array using indices and perform data slicing quickly.
4. Mathematical Functions: NumPy has many built-in mathematical functions like sin, cos, exp, log, etc. which works on arrays, so you can do math calculations on the entire array at once.
5. Logical Operations: NumPy supports logical operations like and, or, and not on arrays, which are very useful in boolean data processing.

# Dimensions
Dimensions are dimensions that refer to the number of levels or levels in a data structure, such as an array, list, or DataFrame.
In Python there are several dimensions such as dimension 0, dimension 1, dimension 2, dimension 3, etc.

# The Pandas Method
Pandas is a library in the Python programming language that is used for data analysis and manipulation. Pandas is very popular among data scientists, data analysts, and developers because it provides powerful tools for managing and analyzing tabular data, such as data in the form of tables or spreadsheets.
## Here are some of the main meanings and uses of Pandas in Python:
1. Data Structures: Pandas provides two main data structures, namely DataFrame and Series. DataFrame is a two-dimensional table similar to a spreadsheet, while Series is a one-dimensional data structure similar to an array or list.
2. Data Manipulation: Pandas allows you to perform various types of data manipulation operations, such as merging data, selecting columns, grouping data, sorting, and more. This makes it very useful for cleaning and processing data before further analysis.
3. Import and Export Data: Pandas supports a variety of file formats, including CSV, Excel, SQL, JSON, and more. You can easily import data from those files into a DataFrame and save your DataFrame in different formats.
4. Exploratory Data Analysis (EDA): Pandas is an essential tool for EDA. You can quickly analyze descriptive statistics, create plots, and gain an initial understanding of your data.

# Data Selection and Data Frame
## Data selection in Python is the process of selecting, retrieving, or accessing certain subsets or parts of data in various types of data structures, such as lists, tuples, strings, NumPy arrays, Pandas DataFrames, and others. The main purpose of data selection is to allow working with specific or relevant data in the context of a programming or data analysis task.

Data selection can involve various operations, such as:
1. Using Index: Retrieves a specific element in a data structure by referring to the index or position of the element. Indexes usually start at 0 (zero) in many data structures in Python.
2. Slicing: Taking chunks of data by selecting a number of sequential elements in the data structure. This is useful for retrieving multiple elements sequentially.
Data selection is one of the important aspects of programming and data analysis, because it allows you to extract the necessary information from larger and more complex datasets.

## Data Frame is a very powerful two-dimensional tabular data structure in the Pandas library in Python. A DataFrame is a collection of data arranged in rows and columns, similar to a table in a database or spreadsheet. Each column in a DataFrame can have a different data type (for example, string, integer, float) and have a unique name.

DataFrames are very useful for managing, analyzing, and manipulating data because they provide the ability to:
1. Storing Data: DataFrames can be used to store data from various sources, including CSV files, Excel, databases, or manually created data.
2. Indexing Data: You can access and refer to data in a DataFrame using column names and row indexes which makes it easier to search and filter data.
3. Data Processing: DataFrame supports various data operations such as sorting, filtering, merging, pivoting, aggregation and statistical processing.
DataFrame is one of the most commonly used data structures in data analysis and data science using Python. It makes working with large and complex data easier and more efficient.

# Loc and Iloc
- LOC is used to access data based on a label or index name.You use loc by specifying the label (name) of the row and column index you want to access.loc works in an inclusive way, which means it will include upper and lower bounds when selecting data.

- ILOC is used to access data based on the position of a numeric index (integer index). iloc functions in an exclusive way for upper bounds and inclusively for lower bounds when selecting data.

