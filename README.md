Amazon Sales Analysis (March – June 2024)
Overview
This project analyzes Amazon sales data from January to April 2024, consisting of 128,974 rows and 17 columns. The analysis involves data preprocessing and the creation of an interactive dashboard in Power BI to provide insights into sales trends, product performance, and customer behavior.
Dataset Details
The dataset includes sales transactions with the following key attributes:
Dataset Details
The dataset includes sales transactions with the following key attributes:
•	Index – Row index
•	Order ID – Unique identifier for each order
•	Date – Date when the order was placed
•	Status – Order status (Completed, Pending, Canceled, etc.)
•	Fulfilment – Fulfillment method used
•	Sales Channel – Platform through which the sale was made
•	Ship Service Level – Shipping priority and method
•	Category – Product category
•	Size – Product size
•	Courier Status – Shipping status
•	Qty – Number of units sold
•	Amount – Revenue generated per order
•	Ship City – City to which the product was shipped
•	Ship State – State to which the product was shipped
•	Ship Postal Code – Postal code of the shipping address
•	B2B – Indicates if the order was a business transaction
•	Fulfilled By – Fulfillment entity (has 83,890 missing values)
•	
Data Preprocessing
To ensure clean and accurate analysis, the following preprocessing steps were performed:
•	Handling Missing Values – Replaced or removed missing data appropriately.
•	Duplicate Removal – Eliminated duplicate entries to maintain data integrity.
•	Data Type Conversion – Adjusted date formats and numerical values for consistency.
•	Outlier Detection – Identified and handled anomalies in sales, profit, and discounts.
•	Feature Engineering – Created new fields such as ‘Delivery Duration’ and ‘Discount Percentage’ for better insights.
Power BI Dashboard
An interactive Power BI dashboard was developed to visualize key metrics, including:
•	Total Sales & Profit Analysis – Monthly trends of revenue and profitability.
•	Top-Selling Products – Identifying the best-performing products.
•	Customer Segmentation – Analyzing purchase behavior by location and demographics.
•	Order Trends – Monitoring sales fluctuations over the 4-month period.
•	Returns & Cancellations – Tracking product returns and their impact on revenue.
•	Delivery Performance – Analyzing shipping efficiency and delays.
Tools & Technologies Used
•	Python (Pandas, NumPy, Matplotlib, Seaborn) – For preprocessing and exploratory data analysis.
•	Power BI – For interactive visualizations and dashboard creation.
•	Excel/CSV – For initial data storage and handling.
How to Use
1.	Preprocessed Data: Load the cleaned dataset into Power BI.
2.	Dashboard Exploration: Interact with the visual reports to gain insights.
3.	Filters & Slicers: Apply different filters such as date range, category, and location for deeper analysis.
Conclusion
This analysis provides valuable insights into Amazon’s sales performance over four months, enabling data-driven decision-making for product inventory, pricing strategies, and customer engagement.
For further improvements, predictive modeling can be incorporated to forecast sales trends and customer behavior.
