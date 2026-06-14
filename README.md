
# 🍕 Pizza Sales Analysis — SQL Project

> SQL-powered insights into customer ordering behavior, revenue trends, and product performance across a full year of pizza restaurant sales data.

---

## 📌 Project Overview

This project analyzes one year (2015) of pizza restaurant sales data using SQL. The goal is to uncover insights into customer ordering patterns, sales performance, revenue distribution, and product popularity through data-driven analysis.

The project covers 13 business questions ranging from basic aggregations to advanced window functions.

---

## 🗂️ Dataset

The dataset consists of 4 relational tables:

| Table         | Description                              | Rows   |
| ------------- | ---------------------------------------- | ------ |
| orders        | Order ID, date, and time of each order   | 21,350 |
| order_details | Order line items and quantities          | 48,620 |
| pizzas        | Pizza size and price information         | 96     |
| pizza_types   | Pizza names, categories, and ingredients | 32     |

**Date Range:** January 1, 2015 – December 31, 2015

### Entity Relationship

```text
orders ──< order_details >── pizzas ──< pizza_types
```

---

## 📊 Business Questions Answered

### Basic

1. Retrieve the total number of orders placed.
2. Calculate the total revenue generated from pizza sales.
3. Identify the highest-priced pizza.
4. Identify the most common pizza size ordered.
5. List the top 5 most ordered pizza types along with their quantities.

### Intermediate

6. Find the total quantity of each pizza category ordered.
7. Determine the distribution of orders by hour of the day.
8. Determine the number of pizza varieties available in each category.
9. Calculate the average number of pizzas ordered per day.
10. Determine the top 3 pizza types based on revenue.

### Advanced

11. Calculate the percentage contribution of each pizza category to total revenue.
12. Analyze cumulative revenue generated over time.
13. Determine the top 3 revenue-generating pizza types within each category.

---

## 📈 Key Findings

### Top-Line Numbers

| Metric                      | Value                    |
| --------------------------- | ------------------------ |
| Total Orders                | 21,350                   |
| Total Revenue               | $817,860                 |
| Average Pizzas Sold Per Day | 138                      |
| Highest-Priced Pizza        | The Greek Pizza ($35.95) |

---

### Pizza Size Distribution

Large pizzas dominate customer preferences with 18,526 orders.

| Size       | Orders |
| ---------- | ------ |
| Large (L)  | 18,526 |
| Medium (M) | 15,385 |
| Small (S)  | 14,137 |
| XL         | 544    |
| XXL        | 28     |

---

### Top 5 Most Ordered Pizzas

| Rank | Pizza                      | Quantity Sold |
| ---- | -------------------------- | ------------- |
| 1    | The Classic Deluxe Pizza   | 2,453         |
| 2    | The Barbecue Chicken Pizza | 2,432         |
| 3    | The Hawaiian Pizza         | 2,422         |
| 4    | The Pepperoni Pizza        | 2,418         |
| 5    | The Thai Chicken Pizza     | 2,371         |

---

### Revenue Contribution by Category

| Category | Revenue Share |
| -------- | ------------- |
| Classic  | 26.91%        |
| Supreme  | 25.46%        |
| Chicken  | 23.96%        |
| Veggie   | 23.68%        |

Revenue is evenly distributed across categories, with no category exceeding 27% of total revenue.

---

### Top Revenue-Generating Pizzas

| Pizza                        | Revenue |
| ---------------------------- | ------- |
| The Thai Chicken Pizza       | $43,434 |
| The Barbecue Chicken Pizza   | $42,768 |
| The California Chicken Pizza | $41,410 |

All three top revenue-generating pizzas belong to the Chicken category.

---

### Peak Order Hours

Customer demand peaks during:

* **Lunch Rush:** 12 PM – 1 PM
* **Dinner Rush:** 5 PM – 6 PM

These periods account for the highest concentration of daily orders.

---

## 💡 Business Recommendations

* Prioritize inventory for top-selling pizzas such as Classic Deluxe, Barbecue Chicken, and Hawaiian.
* Maintain sufficient stock for Large pizzas, which account for the highest number of orders.
* Promote Chicken pizzas, as they generate the highest revenue among individual pizza products.
* Run promotional campaigns during off-peak hours to improve sales throughout the day.


---

## 📁 Project Files

```text
pizza-sales-analysis/
│
├── README.md
├── orders.csv
├── order_details.csv
├── pizzas.csv
├── pizza_types.csv
├── pizza-sales-queries.sql
└── pizza-sales-analysis-presentation.pdf
```

---

## 👤 Author

**Zahid Ernical**

SQL Project – Pizza Sales Analysis

