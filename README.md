# Dashboard_Project

This project shows the popularity between Gold Rums and Dark Rums. The data comes from the Big Query public data set.

SELECT date, SUM(volume_sold_liters) AS Aged_Dark_Rum, FROM bigquery-public-data.iowa_liquor_sales.sales WHERE category_name = "Aged Dark Rum" GROUP BY date ORDER BY date;

A similar SQL query got the sum of Gold Rum sales grouped by year.

The dashboard can be viewed here[https://jacobtessers.github.io/Dashboard_Project/].
