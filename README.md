# 🍕 Pizza Sales Data Analysis Using SQL

This project analyzes pizza sales data using SQL to uncover insights related to revenue, ordering patterns, pizza categories, and top-selling items. It demonstrates SQL skills including joins, grouping, filtering, sorting, and business-focused data analysis.

---

## 📌 Project Overview
The Pizza Sales SQL Project explores a real-world dataset that contains pizza orders, product details, and category information.  
The goal is to extract meaningful insights that help in understanding customer behavior, product performance, and overall sales trends.

---

## 📂 Dataset Description

### **Tables Used**
- **orders** – contains order_id, order_date, order_time  
- **orders_details** – contains order_details_id, order_id, pizza_id, quantity  
- **pizzas** – contains pizza_id, size, price, pizza_type_id  
- **pizza_types** – contains pizza_type_id, name, category  

---

## 🧩 ER Diagram (Conceptual)

```
orders (1) ─── (M) orders_details (M) ─── (1) pizzas ─── (1) pizza_types
``` 

---

## 🛠️ SQL Concepts Used
- SELECT statements  
- INNER JOIN  
- GROUP BY  
- ORDER BY  
- Basic Aggregations (SUM, COUNT, AVG)  
- Filtering and sorting  
- Category-wise and size-wise analysis  

---

## 📊 Key Business Questions Answered
- How many total orders were placed?  
- What is the total revenue generated?  
- What is the most common pizza size?  
- Which are the top 5 pizzas by quantity sold?  
- Which category sells the most?  
- Which pizza is the highest priced?  
- What time of the day receives most orders?  
- What is the average number of pizzas ordered per day?  
- How much revenue does each category contribute?  

---

## 📍 Key Insights
- Medium and Large pizzas are the most frequently ordered sizes.  
- Some pizza categories (like Classic & Supreme) generate the highest revenue.  
- Certain pizza types dominate in both quantity and revenue.  
- Peak ordering hours occur during lunchtime and evening.  
- Category performance helps understand customer preferences better.  

---

## 💡 Recommendations
- Promote best-selling pizza categories to increase sales.  
- Maintain stock for frequently ordered sizes.  
- Use ordering time patterns to plan staffing and offers.  
- Adjust pricing or promotions based on category demand.  
- Continue analyzing sales trends regularly for better decision-making.  

---

## 📁 Repository Structure

```
📦 pizza-sales-sql-project
├── README.md
├── queries.sql          # All SQL analysis queries
├── project.pptx         # Presentation file
└── data/                # Dataset files
    ├── orders.csv
    ├── orders_details.csv
    ├── pizzas.csv
    └── pizza_types.csv
```

---

## 👩‍💻 Author
**Shilpa Kondreddy**  
⭐ If you found this project helpful, please star the repository!
