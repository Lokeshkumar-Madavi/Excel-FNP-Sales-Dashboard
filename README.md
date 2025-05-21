
# FNP(Fern N Petals) Sales -Excel

## 1.Purpose of Sales Analysis
Ferns and Petals, a leading gifting platform catering to festive and personal occasions, seeks to optimize its business performance. With a comprehensive dataset containing order, product, customer, and date information. The goal is to identify sales trends, understand customer behavior, and evaluate product performance to support data-driven decision-making.

https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2FLokeshkumar-Madavi%2FExcel-FNP_Sales_Dashboard%2Frefs%2Fheads%2Fmain%2FFNP%2520Sales%2520Data%2520Project%2520%2526%2520Dashboard.xlsx&wdOrigin=BROWSELINK

## 2.Objective

 1. Calculate total revenue generated.

 2. Assess average order and delivery times.

 3. Analyze monthly sales trends for 2023.

 4. Identify top revenue-generating products.

 5. Evaluate average customer spending.

 6. Monitor sales of top 5 performing products.

 7. Determine top 10 cities by order volume.

 8. Examine impact of order quantity on delivery time.

 9. Compare revenue across various occasions.

 10. Identify popular products for each occasion.

## 3.Data Used

CSV Files from FNP :

 * customers.csv: Customer details.
 * products.csv: Product information.
 * orders.csv: Order details. 

## 4.Workflow Breakdown

  1. Data Loading
     * Imported CSV files from Fern N Petals into Power Query: customers.csv, products.csv, orders.csv

 2. Data Cleaning and Transformation
     * Performed data cleaning in Power Query Editor : removed duplicates, unnecessary columns, and transform into standardized formats.

 3. Data Modeling
       * Used Power Pivot with a star schema approach to model data and build accurate table relationships for reporting.
      ![Data Model](https://github.com/user-attachments/assets/71c46bbd-029f-471f-83df-c4f657591e73)


 4. Data Analysis
       * Analyzed data using Pivot Tables and created key KPIs to track revenue, order trends, delivery times, average customer spending.

 5. Dashboard Creation
      * Revenue by Occasion:
         Analyzed revenue distribution across key occasions like Diwali, Valentine’s Day, etc., to identify high-performing events.

     * Product Category by Revenue:
       Evaluated which product categories generate the most revenue.

     * Revenue by Order Time (in Hours):
       Tracked revenue trends based on the hour of order placement to determine peak sales times.
 
     * Revenue by Month:
       Assessed monthly revenue patterns to understand seasonality and identify growth opportunities.

     * Top 5 Products by Revenue:
       Identified the five highest-earning products to spotlight bestsellers and customer preferences.

     * Top 10 Cities by Orders:
        Highlighted cities with the highest number of orders to target key markets and optimize logistics.

     ![FNP Dashboard](https://github.com/user-attachments/assets/b008a08c-38b1-4dbd-9016-e53337f97921)


## 5.Executive Summery

This Sales Analysis Dashboard provides a comprehensive overview of sales performance, customer behavior, and product trends for FNP (Ferns N Petals). The dataset includes 1,000 total orders, generating a total revenue of ₹35,20,984, with the average customer spending ₹3,520.98. The average order-delivery time is 5.53 days, indicating moderately prompt fulfillment across operations.

## 6.Key Insights

 1. Sales Overview
     * Total Orders: 1,000
     * Revenue: ₹35.2 Lakhs
     * Avg. Order Value: ₹3,520.98
     * Avg. Delivery Time: 5.53 days


2. Revenue by Occasion
      * Top: Anniversary, Raksha Bandhan (>₹6.5L each)
      * Low: Valentine’s Day, Diwali


3. Product Category Performance

    * Best: Flowers (>₹11L), Sweets, Soft Toys
    * Low: Mugs, Plants


4. Time-Based Revenue Trends
      * Peak Hours: 4 PM – 9 PM
      *  Peak Months: March, August
       → Run campaigns in evenings; ramp up for festival months.

5. Top Products
      * Bestsellers: Magnam Set, Quia Gift, Dolores Gift, Harum Pack (~₹1.2L each)


6. Top Cities by Orders =  Leading: Imphal, Dhanbad, Kavali




