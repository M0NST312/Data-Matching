# Extract Invoice Number

This is a Python script that takes an Excel file containing an invoice number column and extracts the invoice numbers using regular expressions. The cleaned invoice numbers are then added to a new column in the dataframe and exported to a new CSV file.

### Prerequisites
Before running the script, you will need to have the following libraries installed:

pandas
numpy
re
### Usage
Replace the pd.read_excel("") statement with the path to your Excel file.
Run the script.
The script will create a new column with cleaned invoice numbers and export the cleaned dataframe to a new CSV file.
### Functions
The script contains the following function:

clean_invoice(): extracts the invoice number using regular expressions.
### Output
The script creates one output file:

Cleaned_INV.csv: a CSV file containing the cleaned dataframe with a new column for cleaned invoice numbers.
### Conclusion
This script provides a simple way to clean invoice numbers from an Excel file using regular expressions and export the cleaned dataframe to a new CSV file. It can be used as a starting point for more complex data cleaning tasks in Python.
