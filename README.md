# 🛒 E-commerce Customer Behaivor Analysis
**🛠️ SQL, Python**  
Exploratory analysis of customer spending patterns and engagement using SQL and Python (Kaggle Olist E-commerce dataset)
<br>

📎 Rachel Kim  
📅 Date: 2025.07 (In Progress, More insights and visualizations to be added. -2025.07.04)  
📚 Individual Project
<br>

---

### 📂 Project Objective
- To understand customer spending behavior and engagement patterns in a Brazilian e-commerce marketplace using SQL and Python. The analysis aims to identify high-value customers, spending distributions, and potential reactivation opportunities through behavioral metrics.  

### 📂 Dataset Description
- Source: Olist Brazilian E-commerce Public Dataset from Kaggle  
- Period: September 2016 – August 2018  
- Tables Used: orders, order_payments, order_items, customers, order_reviews, geolocation, etc.  
- Granularity: Order-level transactions linked with customer, product, and seller details.  

### 📂 Key Analyses Performed
- Total spending and last order date of each customer  
- Top 20 high-spending customers: amount and engagement timeline
- Log-scaled distribution of customer spending
- KDE plot of last order dates to examine customer activation patterns
- Segmentation of top 10% customers for retention opportunities
- Visualization of average basket size per customer (planned)

### 🛠️ Tools & Technologies
- SQL (SQLite via pandas.read_sql_query)
- Python (pandas, matplotlib, seaborn)
- Google Colab
- Data wrangling, transformation, and visual storytelling
