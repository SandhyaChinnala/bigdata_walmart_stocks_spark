# bigdata_walmart_stocks_spark

BigData Engineering Analysis Project on Walmart Stocks dataset using Apache Spark.

Technologies Used: Hadoop, HDFS, SQOOP, Apache Hive, Apache SPark - PySpark & Spark SQL, MySQL, Power BI

the columns in the walmart stocks dattaset:
The Date column refers to the date the data was captured. 

The Open column refers to the first price of the day for the stock. 

High and Low refer to the highest and lowest price the stock reached during the day, respectively. 

When the market closes, the last price recorded is the Close price. Finally, the number of shares traded is captured in the Volume column.

The adjusted close is a number that the data provider - Yahoo, in this case - calculates after considering stock splits and dividend payments. 

The Adj. Close column reflects this value.

Today (imagining we are in late 2012), the adjusted close and the close are the same. Naturally, 
no splits or dividends occurred between 4 P.M. and now. As we go back in time, however, we begin to encounter these events, 
and the close and adjusted close values correspondingly diverge.

If we look back to the first trading day in 2000, we see a close of $25.00 and an adjusted close of $5.36. The most recent close we see is $46.73.

If we compare just the closing prices, it seems like an investment in 2000 would have grown by less than 100%. 

If we instead compare the adjusted closes, the same investment would have grown almost 800%. The adjusted close allows us to incorporate events 
like splits and dividends into our ROI calculations.
