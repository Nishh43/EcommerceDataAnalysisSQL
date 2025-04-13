# 📊 Target Brazil: E-commerce Analytics Case Study (2016–2018) 

Welcome to a comprehensive case study analyzing **Target's Brazilian e-commerce operations** from 2016 to 2018. In this repository, we delve into a rich dataset comprising 100,000 orders placed between 2016 and 2018, leveraging **SQL** for deep data exploration to extract actionable insights about **customer behavior, logistics performance, payment trends, and sales evolution**. 

## 🎯 Objective

To help Target optimize its Brazilian e-commerce strategy through **data-driven decisions** by:

- Understanding **customer distribution and behavior**
- Analyzing **order volume trends** and **seasonality**
- Evaluating **logistics efficiency** and **delivery accuracy**
- Investigating **economic impact** via payment patterns and order value
- Recommending improvements in **regional operations and customer experience**


### Dataset Overview
Explore the extensive dataset, available [here](https://drive.google.com/drive/folders/1TGEc66YKbD443nslRi1bWgVd238gJCnb), organized into 8 CSV files:

1. **customers.csv:** Information about consumers and their locations.
2. **sellers.csv:** Details of registered sellers.
3. **order_items.csv:** Unique IDs, products, and shipping information for each order.
4. **geolocation.csv:** Geographical details including zip codes and coordinates.
5. **payments.csv:** Payment details for each order.
6. **orders.csv:** Order-specific information, statuses, and timestamps.
7. **reviews.csv:** Customer reviews with scores and comments.
8. **products.csv:** Product details, categories, and dimensions.

### Dataset Schema
![Dataset Schema] https://drive.google.com/file/d/16lB1kFnOa2DmwMrVm2p6ObnDjpIYhrrC/view?usp=sharing

The ER diagram (included below) shows how these tables are connected via keys like order_id, product_id, customer_id, and zip_code_prefix.
![image](https://github.com/user-attachments/assets/f9a83d4c-1560-4682-8e05-77d1bb347b86)

> Data spans from **2016 to 2018**, representing the full online retail funnel—from browsing to delivery and review.

## 🧪 Analysis Modules & Key Questions

### 1. 📦 Customer Profile & Order Distribution

- What is the time range of order activity?
- How many unique cities and states do customers come from?
- What are the top regions with the highest customer density?

### 2. 📈 Trends & Seasonality

- Are orders increasing year-over-year?
- What is the monthly seasonality pattern?
- During which time of day are most orders placed? *(Dawn, Morning, Afternoon, Night)*

### 3. 🌎 Regional Demand & Logistics

- How are orders distributed across Brazilian states?
- What are the monthly order counts per state?
- Which states have the fastest or slowest delivery?

### 4. 💸 Economic Impact & Price Trends

- What is the YoY % increase in total order value (Jan–Aug, 2017 vs. 2018)?
- What are the average order and freight costs per state?
- How do payment installment behaviors vary?

### 5. 🚚 Delivery Performance

- What's the actual delivery time vs. estimated?
- Which states consistently deliver faster than expected?
- How can freight cost variation inform better shipping strategy?

### 6. 💳 Payment Preferences

- What are the most popular payment types each month?
- How do installment plans impact order volume?
- Which payment methods trend during specific seasons?

### Getting Started
1. Clone this repository.
2. Download the dataset from the provided Google Drive link.
3. Follow the Python notebooks notebooks or scripts for detailed analysis.

## 🛠️ Tools & Tech

- SQL (BigQuery dialect)
- Google BigQuery & Datalab (for exploration)
- Excel/Tableau/Power BI (for visualization, optional)
- Markdown (for documentation)

## 📌 FAQs & SQL Concepts Covered

✅ `INFORMATION_SCHEMA.COLUMNS`  
✅ `COUNT()`, `DISTINCT`, `AVG()`  
✅ `INNER JOIN` vs `LEFT JOIN` vs `RIGHT JOIN`  
✅ `CTEs`, `LEAD()`, `LAG()`  
✅ `TIMESTAMP_DIFF` vs `DATE_DIFF`  
✅ Filtering strategies, grouping logic, and partitioning 
