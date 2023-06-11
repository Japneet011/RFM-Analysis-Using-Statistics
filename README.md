# RFM-Analysis-Using-Statistics
This my RFM Analysis project. RFM Analysis is a businees concept.
Lookout my RFM Word Document to check what is RFM Analysis and why it is important. 

Data for RFM Excel file contains raw data which tells us about our Customer id, Order Number, Sales, Order Date and on sheet 2 there is table on which we have to rate our customer segment on the basis of the RFM score.

RFM Project contains my project - 
On first sheet you will find the raw which we analyzed and formatted a little.

On second sheet is all about our customer segmentation which we will use later to rate our customers based on RFM scores

Third sheet is a pivot table which will tell last date of purchase of our customer, total orders given by single customer id and total sales made through that customer.

4 th sheet RFM table is the sheet where real magic happens where we have taken customer id, recent purchase date, Sale order count and total sales from previous sheet.
First we will calculate how many days has been since a particular cutomer purchased from us this will help in Calculating Recency(R) 

RFM Scoring-
After this we we have to give scores which will be in range of 1-5 and for giving scores first we need to calculate values and this values can be calculate using Percentile, Quartiles, Min and Max.

For R we will take values from Days since our last purchase because it will show recently our customer ordered from us and for this we can use percentiles which will tell where our most data lies and we will calculate 25,50,75th percentiles and max and min values and score than in descending order because the less the value the less our recency.

For F we will take values Sales order count from  because it will show frequency of customer and for this we can use percentiles which will tell where our most data lies and we will calculate 25,50,75th percentiles and max and min values and score than in ascending order because higher the value higher the frequency.

For M will take values  FROM TOTAL sales because it will show monetary value of a customer for this we can use percentiles which will tell where our most data lies and we will calculate 25,50,75th percentiles and max and min values and score than in descending order because higher the value the higher thee monetary value.
Instead of percentiles we can also use quartiles.

Now we will give R score, F score, M score on sheet 4 using the scores which we gave to our percentile values using Vlooup.
And we will calculate our RF score and RFM score by concatinanting and will give customer segment ratings using customer segment values based on RF score which will help in knowing our customers better and in future tracking them create further analysis on how to retain them and how deal with customers wit low RFM score.
