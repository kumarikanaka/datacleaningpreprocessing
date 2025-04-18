1. Import the Dataset
Open Excel.

Go to File → Open → Browse and select your .csv file (e.g., Superstore_Sales.csv).

2. Inspect the Data
Scroll through the dataset to:

Identify empty cells, inconsistent formats, or outliers.

Check for column names, correct types (e.g., Order Date, Sales should be dates and numbers).

3. Remove Duplicates
Select all data (Ctrl + A).

Go to Data tab → Remove Duplicates.

Select the appropriate columns to check for duplicate rows.

4. Handle Missing Data
Use filters to find blank cells in key columns.

Options:

Delete rows with missing critical data (e.g., missing Sales).

Fill in missing values (using average or previous row if applicable).

5. Convert Order Date to Month-Year Format
Insert a new column:

Use formula:

excel
Copy
Edit
=TEXT([@OrderDate], "mmm yyyy")
Rename column to Month-Year.

6. Correct Data Types
Ensure:

Order Date is a Date type (Format Cells → Date).

Sales, Profit are Currency or Number type.

Region, Category are Text.
