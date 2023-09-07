# TASK 3

# INTRODUCTION

This task showcases my understanding of advanced Excel formulas that were used to determine some key performance indicators in the sales data set used.

# ACTIVITY:
Calculate the following:
1. The average revenue generated from each sale of Paseo
2. The number of sales made in the Government and Midmarket segments
3. The total revenue generated from the sales of 'Montana' in Canada
4. The highest unit of goods sold in Country, Segment and Month 
5. The total profit made in December

# SKILLS DEMONSTRATED

Data Manipulation
1. The use of the 'AverageIF' function
2. The use of the 'CountIF' function
3. The use of the 'SumIF' function
4. The use of 'Xlookup' and 'Vlookup' functions

# RAW DATA

![EXCEL 3](https://github.com/SheyGreene/ANALYSIS-ON-SALES-DATA-II/blob/main/EXCEL%203.png)

# DATA MANIPULATION

The average sales for the product Paseo were determined by using the 'AVERAGEIF' function.
I calculated by:
=AVERAGEIF(highlighted the entire 'PRODUCT' column, followed by the criteria, which is the name of the product 'PASEO', then the averange_range was specified by HIGHLIGHTING the entire 'SALES' column.)
This generated the average revenue for the number of Paseo products sold.

The Total number of sales made in Government and Midmarket was calculated by using the 'COUNTIF' and SUM' functions.
The number of sales made in Government and Midmarket was determined by using:
=COUNTIF (highlighted the entire 'SEGMENT' column, followed by the criteria 'GOVERNMENT' and 'MIDMARKET'

I calculated the total number of sales by:
=SUM (the values for Government and Midmarket gotten from using the COUNTIF function)

The Total Revenue of Montana in Canada was determined by using the 'SUMIFS' function.
This function expands the number of criteria ranges and criteria that can be applied.
This was calculated:
=SUMIFS (highlighted the 'SALES' column, followed by the 'COUNTRY' column and the criteria 'CANADA', followed by the 'PRODUCT' column by the criteria 'MONTANA')

![EXCEL 3(1)](https://github.com/SheyGreene/ANALYSIS-ON-SALES-DATA-II/blob/main/EXCEL%203(1).png)

The highest unit sold was determined by using the 'MAX' function
=MAX(highlighted the entire UNITS SOLD column.)

The Highest Unit Sold in the Segment, Country and Month was determined by using XLOOKUP and VLOOKUP functions
VLOOKUP is used to find things in a table or a range in a row.
=VLOOKUP (what you want to look up, Where you want to look for it, The column number in the range containing the value to return, return an approximate or exact match, which is indicated as 1/TRUE or 0/FALSE).

Month with the Highest Unit Sold: =VLOOKUP('Highest Unit Sold', highlight the entire entire column containing 'Units Sold' to the column containing the 'Month' column, FALSE)

XLOOKUP has the same function as the VLOOKUP function but it is available in Excel 2016 and 2019.

=XLOOKUP(lookup_value (the value to search for), lookup_array (the range or array to search), return_array (the range or array to return), (if_not_found), (match_mode), (search_mode)) P.S. The last three arguments are optional, while the first three are required.

Country and Segment with the Highest Units Sold:
=XLOOKUP(lookup_value (Highest unit sold), lookup_array (units sold), lookup_range (country), "N/A (exact match by default))
=XLOOKUP(lookup_value (Highest unit sold), lookup_array (units sold), lookup_range (segment), "N/A (exact match by default))

# CONCLUSION
I expanded my knowledge on the use of advanced Excel formulas with this task.
