This is a Data Cleaning Project in SQL.

The data source is an excel file containing 56477 rows of data.

Steps followed:

1.	Standardized Date Format to get rid of the hour which was not needed.
2.	Populated Nulls in Property Address Data Depending on ParcelID.
3.	Split Property Address into Individual Columns (Address, City) Using SUBSTRING.
4.	Split Owner Address into Individual Columns (Address, City, State) Using PARSENAME.
5.	Changed Y and N to Yes and No in "Sold as Vacant" Column.
6.	Removed Duplicates.
7.	Deleted Unused Columns.

