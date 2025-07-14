# Online Retail Sales Analysis Using Python
This project is an exploratory data analysis (EDA) of an E-Commerce retail dataset to uncover customer purchasing behavior, product performance, and sales trends over time. The analysis is conducted using Python and focuses on identifying key patterns that can help optimize marketing, inventory, and sales strategies.

## Project Objective
The goal of this project is to perform a comprehensive analysis of an online retail dataset to:

Understand how sales and customer behavior change over time (monthly, weekly, hourly). Identify top-performing products, countries, and customers. Highlight key patterns in order frequency and customer retention. Extract actionable insights to improve business decision-making. This project demonstrates proficiency in data cleaning, exploratory data analysis, and data visualization using Python.

## Dataset Used
- <a href = "https://github.com/alina-khan-1/Python-Online-Retail-data-analysis/blob/main/Online%20Retail%20Data%20Set.csv">Online Retail Orders Dataset</a>
The dataset contains transactional data from a UK-based online retail store over a period spanning late 2010 and full-year 2011.

## Key Questions Answered
- When do customers shop the most (monthly, weekly, daily, hourly)?
- Which countries generate the most revenue?
- Which products are top sellers (by quantity and revenue)?
- Who are the best customers in terms of order frequency and revenue?
- How many customers are repeat vs one-time buyers?

## Tools & Libraries
Environment: Visual Studio Code + Jupyter extension
Language: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn

## Process
**1. Environment Setup**
- Installed required libraries via pip
- Configured VS Code with Jupyter extension

**2. Data Loading**
- Loaded the dataset using pandas.read_csv()

**3. Data Cleaning**
- Handled missing values and nulls
- Removed duplicates and invalid entries
- Converted InvoiceDate to datetime format
- Filtered data to focus on completed (non-cancelled) transactions

**4. Exploratory Data Analysis (EDA)**
- Time-based analysis: Monthly, Weekly, Hourly trends
- Geographic analysis: Country-wise revenue and orders
- Product analysis: Top products by quantity and revenue
- Customer analysis: Order frequency and total spend per customer

## Key Insights & Visuals
**1. Monthly Sales Trend**
- Sales peak toward the end of the year (Nov–Dec), likely due to holiday season shopping. Sales are lowest at the start of the year, indicating seasonality.

**2. Yearly Sales Trend**
- 2011 had significantly higher sales compared to 2010, primarily because the dataset contains data for the full year in 2011, while only one month is available for 2010.

**3. Order Count by Year**
- Confirms that 2011 had more orders, making it the dominant contributor to the dataset’s insights.

**4. Hourly Sales Trend**
- Most purchases occur between 9 AM to 1 PM, peaking at 12 PM. Activity drops in the afternoon and is low in the evening, possibly due to lunch breaks and working hours.

**5. Weekday vs Weekend Sales (Pie Chart)**
- 91.2% of sales occur on weekdays; weekends only make up 8.8%. Indicates stronger customer engagement during workdays.

**6. Weekly Sales Trend**
- Thursday has the highest sales, while Saturday shows nearly zero activity. Indicates a pattern where mid-to-late weekdays are key business days.

**7. Combined Time Analysis**
- Sales spike mid-month, likely tied to paydays. Mornings dominate in hourly analysis, and weekdays outperform weekends across the board.

**8. Country-Wise Sales**
- The United Kingdom overwhelmingly dominates both sales and order count—most customers are based there.

**9. Portugal vs Australia**
- Despite equal invoice counts (57), Australia’s total revenue ($33,376) is far higher than Portugal's, suggesting higher-value orders.

**10. Other Countries**
- "Cyprus" (16 orders, $13.5k) and "Singapore" (7 orders, $21.2k) show strong value per order, while "Iceland" and "Unspecified" have weaker sales, despite similar order counts.

**11. Top-Selling Products (Quantity vs Revenue)**
- 23843: 80,995 units and $168,469 — high in both
- 23166: 77,916 units but only $81,417 — likely low-priced
- 22423: $142,265 sales, fewer units — high-value item
- 85099B: Well-balanced with 46,078 units and $85,040 revenue

**12. Poor-Performing Products**
- Products like 47579, 90021, 85170A sold only 1 unit each—possibly failed launches or niche items.

**13. Low-Sale Items**
- Some products like "PADS" ($0.003) or "84227" ($0.42) might be freebies, samples, or pricing errors.

**14. Top-Spending Customers**
- Customer 14646.0 spent $280,206, followed by 18102.0 ($259,657) and 17450.0 ($194,390). Heavy spenders contribute a large share of revenue.

**15. Most Loyal Customers (Order Count)**
- Customer 17841.0 placed 7,676 orders, indicating high engagement and repeat business.

**16. Average Orders Per Customer**
- On average, each customer made 4.27 orders, suggesting a moderately loyal customer base.

**17. Repeat vs One-Time Buyers**
- 1,493 customers made only 1 order
- Only 1 customer reached 209 orders
- Shows a classic drop-off pattern common in retail

## Final Summary & Recommendations
**Peak Sales Time:** Late-year months (holiday season), weekdays, and mornings
**Customer Behavior:** Strong weekday shopping activity, possibly during breaks or work hours
**Product Strategy:**
  - Push high-volume + high-value products
  - Reassess or discontinue low-performing items
**Geo Focus:** Target UK customers with special offers
**Customer Loyalty:** Develop strategies to turn one-time buyers into repeat customers
**Marketing:** Send email campaigns around mid-month and late mornings

## Skills Demonstrated
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Business Thinking with Data
- Time Series Aggregation (hourly, weekly, monthly)
- Visual Storytelling with Python (Matplotlib + Seaborn)
- Customer Segmentation and Product Strategy
