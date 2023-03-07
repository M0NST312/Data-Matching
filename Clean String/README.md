# Remove Unwanted Text
This Python script reads an excel file containing customer names, cleans the names by removing unwanted text and saves the cleaned data to a new excel file.

### Libraries Used
pandas
numpy
re
### Usage
Replace path/to/excel_file on line 5 with the path to your input excel file.
Run the script.
Functionality
The script cleans customer names using the following steps:

Remove any text within parentheses.
Remove 'Family' or 'Store' if they occur in the name.
Find and remove any string that begins with either 'KT' or 'AVI' followed by any digits and any combination of letters, digits, and special characters.
### Inputs
The script takes an input excel file containing a column named 'CustomerName' with the customer names to be cleaned.

### Outputs
The script outputs a new excel file named "CleanedData.xlsx" with the cleaned customer names in a column named 'Clean_Customer_Name'.

### Example
Suppose the input excel file contains the following customer names:
CustomerName
```
John (Smith) Family KT54321 
Jane Doe Store AVI09876
```
The output excel file will contain the following cleaned customer names:
```
CustomerName              Clean_Customer_Name
John (Smith) Family KT54321      John Smith
Jane Doe Store AVI09876          Jane Doe
```
