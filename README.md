# Weather-data-analysis
In this project:
___________________________________________________________________________________________________________________________________

Questions to answer:

1 - Find all the unique 'Wind Speed' values in the data.
2 - Find the number of times when the 'Weather is exactly Clear'.
3 - Find the number of times when the 'Wind Speed was exactly 4 km/h'.
4 - Find out all the Null Values in the data.
5 - Rename the column name 'Weather' of the dataframe to 'Weather Condition'.
6 - What is the mean 'Visibility' ?
7 -  What is the Standard Deviation of 'Pressure'  in this data?
8 - Whats is the Variance of 'Relative Humidity' in this data ?
9 - Find all instances when 'Snow' was recorded.
10 - Find all instances when 'Wind Speed is above 24' and 'Visibility is 25'.
11 - What is the Mean value of each column against each 'Weather Conditon' ?
12 - What is the Minimum & Maximum value of each column against each 'Weather Conditon' ?
13 - Show all the Records where Weather Condition is Fog.
14 - Find all instances when 'Weather is Clear' or 'Visibility is above 40'.
15 - Find all instances when :
    A. 'Weather is Clear' and 'Relative Humidity is greater than 50' or B. 'Visibility is above 40'

____________________________________________________________________________________________________________________________________

Geting information about dataset:

info() - Provides basic information about the dataframe.
index - This attribute provides the index of the dataframe.
columns - It shows the name of each column.
dtypes - It shows the data-type of each column.
shape - It shows the total no. of rows and no. of columns of the dataframe
nunique() It shows the total no. of unique values in each column. It can be applied on a single column as well as on whole dataframe.
unique() - In a column, it shows all the unique values. It can be applied on a single column only, not on the whole dataframe.
value_counts() - In a column, it shows all the unique values with their count. It can be applied on single column only.
count() - It shows the total no. of non-null values in each column. It can be applied on a single column as well as on whole dataframe.

head() 
groupby()
getgroup()
isnull() & notnull()
rename()
mean() 
std()
str.contains
And (&) Operator
Or (|) operator
min() % max()
