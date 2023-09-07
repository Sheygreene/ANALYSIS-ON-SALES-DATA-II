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


