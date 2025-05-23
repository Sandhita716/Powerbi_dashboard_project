MAHADEV E-COMMERCE

This sales dashboard for Mahadev E-Commerce providing a snapshot of key performance indicators(KPI).
Overview of the Dashboard:
The dashboard is organized to provide a comprehensive view of sales performance across different dimensions.
Key matrics displayed at the top include:
•	Total Sales Amount(438k)-Overall revenue generated.
•	Total Profit(37k)-Total Profit earned from Sales.
•	Total Quantity Sold(6k)-Total number of items sold.
•	Average Order Value(AOV)(121k)-The average amount spent per order.

Further break downs by various categories:
•	Sum of amount by state-shows sales distribution across different states with Maharashtra leading.
•	Sum of Quantity by Category-Highlights the proportion of quantity sold for furniture(17%),
Electronics(21%),and clothing(63%),with clothing being the dominant category.
•	Profit by Month-Illustrates the monthly profit trend, showing fluctuations throughout the year with negative profit in July and August.
•	(Sum of Amount by CustomerName): Displays the total sales amount contributed by different customers, with Harivansh being the top contributor.
•	Payment Mode (Sum of Quantity by PaymentMode): Shows the distribution of payment methods used, with COD (Cash on Delivery) being the most popular.

•	Product Sub-Category (Sum of Profit by Sub-Category): Details the profit generated by different product sub-categories, with Printers and Bookcases being the most profitable.

DAX (Data Analysis Expressions):


 * Total Profit:
Profit1 = SUM((Details[Profit]))
 * Total Quantity Sold:
Quantity1 = SUM(Details[Quantity])
 * Average Order Value (AOV):
AOV = [Amount]/[Quantity1]
•	Amount
Amount 1 = SUM(Details[Amount])

In summary, the dashboard provides a valuable overview of Madhav Ecommerce's sales performance across various dimensions. Further in-depth analysis of the trends and underlying data can lead to business growth and optimization. To know the exact DAX, access to the Power BI file or the data model would be required.
