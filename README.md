# DSA-DATA-ANALYSIS
AMAZON CASE FILE 
STEPS TAKEN IN ANALYSING THE DATA.

I coppied the Amazon data set on a new woorkbook, then converted rhe whole data to a table. 
Saperated the category column by delimeter.
The datatypes was changed on the necessary columns 
Some columns like image link, user name, user review were deleted from the table to relieve space from the data set. 
The potential revenue was calculated by multiplying the actual_price by the rating_count
The Price bucket column was calculated using the formula =IF(D2<200,"<₹200",IF(D2<500,"₹200–₹500",">₹500"))
After calculation the whole table was summarized on a pivot table 
The pivot table was used to to plot the chart appropriate for each 
