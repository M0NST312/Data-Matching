# Clean Data Regex

This script reads in an Excel file with a column containing company names, cleans the names using regular expressions and saves the cleaned data to a new CSV file.

The script uses the pandas and numpy libraries to read in and manipulate the data, as well as the re library for regular expressions.

The cleantext function defined in the script takes a string argument and applies the following transformations to it:

Converts the string to lowercase (if it's not already in lowercase)
Removes any parentheses from the string
Removes certain keywords (e.g. "proprietary", "limited", "pty", "ltd", "inc") from the string
Strips any whitespace from the string
Converts the string to uppercase
The cleaned data is stored in an array, which is then used to create a new column in the original dataframe containing the cleaned names. The cleaned data is then exported to a new CSV file.

### Usage
Ensure that the pandas, numpy, and re libraries are installed.
Update the file path in line 5 of the script to point to the Excel file you want to read in.
Run the script. The cleaned data will be saved to a new CSV file in the same directory as the script.
Note: This script assumes that the column containing the company names in the Excel file is named "Payee". If your data has a different column name, you will need to update line 13 of the script accordingly.
