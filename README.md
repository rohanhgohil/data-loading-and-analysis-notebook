# Data Loading and Analysis
This repository contains Python code to **load**, **analyze**, and **perform various operations** on the Titanic passenger data.

### 1. Loading a Tabular Data File
- Load the "titanic.csv" dataset into a DataFrame and print the first 5 rows.
- Drop the "SibSp", "Parch", and "Ticket" columns and print the first 5 rows.
- Convert the "Survived" column to boolean data type and print the first 5 rows.

### 2. Previewing the DataFrame
- Printing the index and column names of the DataFrame.
- Printing the size of the DataFrame.
- Printing the amount of rows per each column without missing values.
- Printing the unique values for the "Sex" and "Embarked" columns.
- Printing the number of rows with the same specific value in the "Embarked" column.
- Printing the number of passengers who survived and the survival percentage.

### 3. Summary Statistics
- Printing the maximum age of the Titanic passengers.
- Printing the average age and average ticket price.
- Calculating the number of passengers who survived using the sum method.
- Printing a full statistical summary using the describe method and find the age value that 25% of passengers are smaller than.

### 4. Sorting and Ranking
- Sorting all rows in the DataFrame based on the "Age" column in descending order and print the first 5 rows.
- Sorting all rows in the DataFrame based on the "Age" column in descending order and save it in the same DataFrame.
- Sorting the data based on male and female groups, and inside each group, sort the rows by age in ascending order.

### 5. Filtering
- Filtering and keep only the male passengers.
- Filtering out all passengers below the age of 40 and are male.

### 6. Grouping and Aggregating
- Calculating the average ticket price for male and female passengers.
- Calculating the average age for the survived group.
- Calculating the number of passengers who survived grouped by the embarked port.
- Calculating the average age and average price for male and female passengers.
