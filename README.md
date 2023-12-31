EXPLORATORY DATA ANALYSIS -London-Housing-Data.
* IN THIS PROJECT ON THE BASIS OF DATA SET FROM KAGGLE BELOW QUERIES ARE RESOLVED BY USING PYTHON & LIBRARIES COMMANDS: dala analysis, data clean up, data visualization tasks are completed. COMMANDS USED:-
The commands that we used in this project :

* head() - It shows the first N rows in the data (by default, N=5).
* tail () - It shows the last N rows in the data (by default, N=5).
* shape - It shows the total no. of rows and no. of columns of the dataframe.
* size - To show No. of total values(elements) in the dataset.
* columns - To show each Column Name.
* dtypes - To show the data-type of each column.
* info() - To show indexes, columns, data-types of each column, memory at once.
* value_counts - In a column, it shows all the unique values with their count. It can be applied on a single column only.
* unique() - It shows the all unique values of the series.
* nunique() - It shows the total no. of unique values in the series.
* duplicated( ) - To check row wise and detect the Duplicate rows.
* isnull( ) - To show where Null value is present.
* dropna( ) - It drops the rows that contains all missing values.
* isin( ) - To show all records including particular elements.
* str.contains( ) - To get all records that contains a given string.
* str.split( ) - It splits a column's string into different columns.
* to_datetime( ) - Converts the data-type of Date-Time Column into datetime[ns] datatype.
* dt.year.value_counts( ) - It counts the occurrence of all individual years in Time column.
* groupby( ) - Groupby is used to split the data into groups based on some criteria.
* sns.countplot(df['Col_name']) - To show the count of all unique values of any column in the form of bar graph.
* max( ), min( ) - It shows the maximum/minimum value of the series.
* mean( ) - It shows the mean value of the series.

*In this project , dala analysis, data clean up and below exploration has been done.
Q. 1) Convert the Datatype of 'Date' column to Date-Time format. 
Q. 2) Add a new column ''year'' in the dataframe, which contains years only.(B.2) Add a new column ''month'' as 2nd column in the dataframe, which contains month only.
Q. 3) Remove the columns 'year' and 'month' from the dataframe. 
Q. 4) Show all the records where 'No. of Crimes' is 0. And, how many such records are there ?
Q. 5) What is the maximum & minimum 'average_price' per year in england ?
Q. 6) What is the Maximum & Minimum No. of Crimes recorded per area ? 
Q. 7) Show the total count of records of each area, where average price is less than 100000.
