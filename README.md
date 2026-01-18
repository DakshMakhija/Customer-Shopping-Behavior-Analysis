# 🛍️ Customer Shopping Behavior Analysis

An end-to-end data analytics project using **Python, SQL, and Power BI** to analyze customer purchasing patterns and generate business insights.

---

## 📌 Project Overview

This project focuses on understanding:

* Customer spending behavior
* Impact of discounts & subscriptions
* Product performance
* Customer segmentation
* Purchase frequency patterns

The workflow includes:

1. Data cleaning using Python
2. Storing processed data in MySQL
3. Analytical queries using SQL
4. Interactive dashboards in Power BI

---

## 🧰 Tech Stack

* **Python** (Pandas, SQLAlchemy)
* **MySQL**
* **SQL** (CTEs, Window functions, Subqueries)
* **Power BI**
* **GitHub**

---

## 📂 Folder Structure

```
📦 Customer-Shopping-Analysis
 ┣ 📁 data
 ┃ ┗ customer_shopping_behavior.csv
 ┣ 📁 notebooks
 ┃ ┗ Customer_data.ipynb
 ┣ 📁 sql
 ┃ ┗ customer.sql
 ┣ 📁 dashboard
 ┃ ┗ customer_analysis.pbix
 ┗ README.md
```

---

## 🧹 Data Cleaning (Python)

Performed in `Customer_data.ipynb`:

* Checked dataset shape & structure
* Handled missing values in `review_rating` using median
* Renamed columns to snake_case
* Created new features:

  * `age_group`
  * `purchase_frequency_days`
* Removed redundant column (`promo_code_used`)
* Exported clean data to MySQL using SQLAlchemy

---

## 🗄️ Database & SQL Analysis

Table: `cust_data`

### Key Business Queries

* Revenue by gender
* Customers using discount but spending above average
* Top 5 products by review rating
* Shipping type vs average purchase
* Subscriber vs non-subscriber spending
* Discount usage percentage by product
* Customer segmentation:

  * New
  * Returning
  * Loyal
* Top 3 products per category (Window function)
* Repeat buyers vs subscription status
* Revenue by age group

---

## 📊 Power BI Dashboard

### Page 1 – Business Overview

* Total Revenue
* Revenue by Gender
* Location-wise Sales
* Seasonal trends

### Page 2 – Customer Behavior

* Age group vs spending
* New vs returning customers
* Payment preferences
* Subscription impact

### Page 3 – Product Insights

* Top & bottom products
* Discount effectiveness
* Shipping preferences
* Size-color heatmap

---

## 🔍 Key Insights

* Subscribed customers spend more on average
* Discounts increase purchase volume
* Weekly buyers contribute highest revenue
* Clothing category dominates sales
* Middle-aged customers generate maximum revenue

---

## 🚀 How to Run

### 1️⃣ Install Dependencies

```bash
pip install pandas sqlalchemy mysql-connector-python
```

### 2️⃣ Run Python Notebook

```bash
jupyter notebook Customer_data.ipynb
```

### 3️⃣ Load Data into MySQL

* Database: `CD`
* Table: `cust_data`

### 4️⃣ Run SQL Queries

```sql
source customer.sql;
```

### 5️⃣ Open Power BI

* Load data from MySQL
* Open `.pbix` file

---

## 📈 Results

* Built interactive dashboards
* Derived actionable business insights
* Improved decision-making visibility

---

## 🔮 Future Enhancements

* Sales forecasting
* Customer churn prediction
* Customer lifetime value (CLV)
* Machine learning segmentation

---

## 👨‍💻 Author

**Daksh Makhija**
Data Analyst
📧 Email: dakshmakhija978@gmail.com
🔗 LinkedIn: [linkedin.com/in/daksh-makhija-a30892202](https://linkedin.com/in/daksh-makhija-a30892202)  
💻 GitHub: [github.com/DakshMakhija](https://github.com/DakshMakhija)
---

⭐ If you like this project, feel free to star the repo!
