# DataSpark: Illuminating Insights for Global Electronics

## Problem Statement
As part of Global Electronics' data analytics team, you are tasked with conducting a comprehensive Exploratory Data Analysis (EDA) to uncover valuable insights from the company’s data. Your goal is to provide actionable recommendations that can enhance customer satisfaction, optimize operations, and drive overall business growth. Global Electronics, a leading retailer of consumer electronics, has provided you with several datasets containing information about their customers, products, sales, stores, and currency exchange rates. The company seeks to leverage this data to better understand their business and identify areas for improvement.

## Business Use Cases
By analyzing Global Electronics' customer, product, sales, and store data, we aim to identify key insights that will enhance marketing strategies, optimize inventory management, and improve sales forecasting. This will help tailor marketing campaigns, develop better products, plan effective promotions, and decide on store expansions and optimizations. Additionally, understanding the impact of currency exchange rates on sales will allow for better international pricing strategies. Overall, these insights will help Global Electronics increase customer satisfaction and drive business growth.

## Skills Takeaway From This Project
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Python
- Data Management using SQL
- Power BI

## Tools Used
- **Jupyter Notebook and PyCharm**: IDE
- **Python, Pandas**: Data cleaning and exploratory data analysis
- **MySQL**: Database to store and retrieve cleaned data
- **Power BI**: Visualization

## Approach
### Data Cleaning and Preparation
- Check for missing values and handle them appropriately.
- Convert data types where necessary (e.g., dates, numerical values).
- Merge datasets where necessary for analysis (e.g., linking sales data with product and customer data).

### Load Data
- Insert the preprocessed data into an SQL database by creating relevant tables for each data source and using SQL INSERT statements to load the data.

### Power BI Visualization
- Connect SQL to Power BI/Tableau, import the data, and create interactive dashboards.

### Development of SQL and DAX Queries
- Formulate and execute 10 SQL queries to extract key insights from the data. These queries should address important business questions and support the analysis steps below.

## Analysis Steps
### Customer Analysis
- **Demographic Distribution**: Analyze the distribution of customers based on gender, age (calculated from birthday), location (city, state, country, continent).
- **Purchase Patterns**: Identify purchasing patterns such as average order value, frequency of purchases, and preferred products.
- **Segmentation**: Segment customers based on demographics and purchasing behavior to identify key customer groups.

### Sales Analysis
- **Overall Sales Performance**: Analyze total sales over time, identifying trends and seasonality.
- **Sales by Product**: Evaluate which products are the top performers in terms of quantity sold and revenue generated.
- **Sales by Store**: Assess the performance of different stores based on sales data.
- **Sales by Currency**: Examine how different currencies impact sales figures, considering exchange rates.

### Product Analysis
- **Product Popularity**: Identify the most and least popular products based on sales data.
- **Profitability Analysis**: Calculate profit margins for products by comparing unit cost and unit price.
- **Category Analysis**: Analyze sales performance across different product categories and subcategories.

### Store Analysis
- **Store Performance**: Evaluate store performance based on sales, size (square meters), and operational data (open date).
- **Geographical Analysis**: Analyze sales by store location to identify high-performing regions.
- **Sales Channel Analysis**: Assess the performance of online versus physical stores to understand customer behavior across channels.

## Results/Findings

### 1. Customer Demographics and Behavior
- **Age Distribution**: 
  - Customers are evenly distributed across most age groups, with 14-15% in each segment.
  - The **20-30 age group** is slightly underrepresented, making up **10.84%** of customers.
  - The **30-40 age group** has the highest spending in USD, though the difference is minimal across other groups.
  
- **Gender Distribution**:
  - Customer population is **almost equally split between genders**.
  - Both genders show **similar revenue contributions and average order values**.
  - The **top 5 most preferred products** are the same for both genders.

- **Geographical Distribution**:
  - The **USA** leads with the highest number of customers (**7k out of 15k**).
  - Key cities with a large customer base include **Toronto, New York, and Los Angeles**.

### 2. Customer Segmentation
- **Loyal Customers (5-10 orders)** contribute to the highest revenue of **27M USD**.
- **VIP Customers (10+ orders)** generate **15M USD**, while **Occasional Customers (1-4 orders)** contribute **14M USD**.
- **Customer Breakdown**:
  - **42%** are **occasional buyers**.
  - **28%** are **loyal buyers**.
  - **8%** are **VIP buyers**.
  - **22%** of customers have **not placed any orders yet**.

### 3. Sales Analysis by Currency
- **53.6%** of sales are in **USD**, followed by:
  - **EUR: 20.4%**
  - **GBP: 12.7%**
  - **CAD: 8.4%**
  - **AUD: 4.9%**

### 4. Product Analysis
- **Top Performing Categories**: 
  - **Computers** and **Cellphones** have the highest sales, followed by **Music, Movies, Audiobooks**, and **Audio**.
  - In the **Computers** category, **Desktops** lead both in sales and revenue.

- **Profit Margins**:
  - **Music, Movies, Audiobooks** and **Computers** have the highest profit margins, exceeding **60%**.

- **Top-Selling Products**:
  - **WWI Desktop PC2.33 X2330 Black** is the most sold product and also generates the highest profit (**338k USD**).

- **Product Popularity**:
  - **Bluetooth Headphones**, **Movie DVDs**, and **Desktops** are the most popular subcategories.
  - **Games and Toys** have the lowest revenue (**0.72M USD**).

- **Underperforming Products**:
  - **25 products** have **zero sales**, most of which are in the **Chandeliers and Lamps** category.

- **Profit Margin Variations**:
  - The highest profit margin (**66.87%**) is on **Contoso Behind Centrex X15 Grey**.
  - The lowest profit margin (**48.96%**) is on **Contoso In-line Coupler E180 Black**.

### 5. Time-Based Sales Performance
- **Best Quarters**: **Quarter 1 and Quarter 4** have the highest sales.
- **Yearly Revenue**: 
  - **2019** was the best year in terms of revenue.
  - Combined revenue from **2018 and 2019** is higher than the total revenue from the other three years.

### 6. Store Performance
- **Online Store**:
  - Generates **11.4M USD**, which accounts for **21%** of total revenue.

- **Top Offline Stores**:
  - High-performing stores include those in **Nevada, Kansas, Nebraska, Northwest Territories**, and **New Mexico**.

- **Underperforming Stores**:
  - Stores in **Basse-Normandie, Corse, Northern Territory, Franche-Comte** report the lowest revenue.
  - There are also **9 stores** with **zero business activity** (no revenue).

- **Store Size Impact**:
  - Stores with more than **2000 square meters** tend to have higher revenues.

### 7. Revenue by Product
- **Quantity-wise**, the highest sold product is **Movie DVDs**.
- **Revenue-wise**, **Desktops** are the top performers.
- **Air conditioners** have the lowest quantity sold, and **Boxed games** have the least revenue.

### 8. Overall Summary
- **Total Revenue**: **55.76M USD**.
- **Total Profit**: **32.66M USD**.
- **Total Products Sold**: **198k**.
- **Top Three Subcategories by Sales**: 
  - **Bluetooth Headphones**, **Movie DVDs**, and **Desktops**.
- **Least Profitable Category**: **Games and Toys**.

## Screenshots of Reports
Below are the screenshots of the reports generated during the project. These visualizations provide insights into customer demographics, sales performance, store and product analysis.

![Report Screenshot 1](screenshots%20of%20reports/customer%20analysis.png) 
![Report Screenshot 2](screenshots%20of%20reports/sales%20analysis.png) 
![Report Screenshot 3](screenshots%20of%20reports/product%20analysis.png)
