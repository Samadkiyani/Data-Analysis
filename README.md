# Data-Analysis
Data Analysis using Python
The provided code performs a series of analyses and visualizations on a sales dataset to uncover insights into transaction patterns and profitability. It starts by loading the dataset into a pandas DataFrame and performing various operations.

Transaction Profit Analysis: The code calculates the transaction with the lowest profit, the average profit of the top 10% most profitable transactions, and identifies transactions that exceed a specified profit threshold. Additionally, it compares the most profitable transaction’s profit with the median profit and generates a scatter plot to visualize the relationship between profit and order quantity, highlighting the most profitable transaction.

Country-Based Analysis: It calculates the average order quantity for each country, identifies the country with the lowest average order quantity, and compares the number of transactions across countries. The code also calculates the average profit per transaction for each country and creates a bar chart to compare average order quantities across countries.

Throughout, pandas is used for data manipulation and aggregation, while matplotlib is used for visualizing the results through charts. These analyses provide a provisional understanding of key business metrics like profit and sales performance, segmented by various categories such as country and product.
