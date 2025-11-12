<img width="1200" height="630" alt="image" src="https://github.com/user-attachments/assets/72d366de-f5ed-49be-b8c4-06e17634a597" />


<h2>🛍️ Customer Shopping Behavior Analysis</h2>
📊 Data Analytics | Python | SQL | Power BI | PostgreSQL

<h4>📘 Project Overview</h4>
<ul><li>
  This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.
</li>
<li>The goal is to uncover insights into spending patterns, product preferences, customer segmentation, and subscription behavior to guide strategic business decisions.</li>
</ul>



<h4>🧾 Dataset Summary</h4>

Attribute	Details
<ul>
  <li>Rows	3,900</li>
  <li>Columns	18</li>
  <li>Key Features	Age, Gender, Location, Subscription Status, Item Purchased, Category, Purchase Amount, Discount Applied, Review Rating, Shipping Type, Previous Purchases</li>
  <li>Missing Data	37 missing values in Review Rating column</li>
  <li>Data Sources	Simulated customer transaction data</li>
</ul>


<h4>🧠 Data Exploration & Preparation (Python)</h4>

Performed using Pandas, NumPy, and Matplotlib.

<h5>Key steps:</h5>
<ul>
  <li>Loaded and explored dataset using df.info() and df.describe().</li>
  <li>Handled missing data by imputing Review Rating with category-wise median.</li>
  <li>Renamed columns to snake_case format for readability.</li>
  <li>Engineered new features:
  <ol>
    <li>age_group → binned from age.</li>
    <li>purchase_frequency_days → derived from purchase history.</li>
  </ol>
</li>
  <li>Removed redundant columns (promo_code_used dropped after correlation with discount_applied).</li>
  <li>Uploaded cleaned dataset to PostgreSQL for structured SQL analysis.</li>
</ul>

<h4>🧮 SQL-Based Business Analysis (PostgreSQL)</h4>

<h5>Answered key business questions through SQL queries:</h5>
<ol>
  <li>Revenue by Gender – Compared total revenue by male vs. female customers.</li>
  <li>High-Spending Discount Users – Identified discount users spending above average.</li>
  <li>Top 5 Products by Rating – Highest-rated products by customer reviews.</li>
  <li>Shipping Type Comparison – Compared average order value by shipping type.</li>
  <li>Subscribers vs. Non-Subscribers – Spend and revenue comparison.</li>
  <li>Discount-Dependent Products – Top 5 products most frequently purchased with discounts.</li>
  <li>Customer Segmentation – Categorized customers as New, Returning, Loyal.</li>
  <li>Top 3 Products per Category – Using window functions (RANK + PARTITION BY).</li>
  <li>Repeat Buyers & Subscriptions – Measured link between frequent buyers and subscription rate.</li>
  <li>Revenue by Age Group – Contribution of each age group to total revenue.</li>
</ol>

<h4>📈 Power BI Dashboard</h4>

<h5>An interactive Power BI dashboard was developed to visualize key insights, including:</h5>
<ul>
  <li>🧍 Customer Demographics & Segmentation</li>
  <li>💰 Revenue by Category, Age Group, and Gender</li>
  <li>🏷️ Discount Usage & Subscription Trends</li>
  <li>🚚 Shipping Performance (Standard vs. Express)</li>
  <li>⭐ Product Ratings and Top Performers</li>
</ul>
<hr>

<img width="637" height="362" alt="image" src="https://github.com/user-attachments/assets/9bd85f71-8cac-4861-a07f-eb914312c354" />


<h4>💼 Business Recommendations</h4>
<ul>
  <li>Boost Subscriptions – Highlight exclusive subscriber perks.</li>
  <li>Reward Loyalty – Implement point-based rewards for repeat buyers.</li>
  <li>Optimize Discounts – Monitor margin impacts of discount-driven sales.</li>
  <li>Product Positioning – Feature top-rated, high-margin products in campaigns.</li>
  <li>Targeted Marketing – Prioritize high-revenue age brackets and express-shipping users.</li>
</ul>


<h4>🧰 Tools & Technologies</h4>

<h6>Tool	Purpose</h6>
<ul>
  <li>🐍 Python	Data cleaning & exploratory analysis</li>
  <li>🐘 PostgreSQL	Structured SQL queries & analytics</li>
  <li>📊 Power BI	Data visualization & storytelling</li>
  <li>🧮 Pandas, NumPy	Data manipulation & transformation</li>
  <li>💻 GitHub	Project versioning & documentation</li>
</ul>

<h4>📂 Repository Structure</h4>


📁 Customer-Shopping-Behavior-Analysis/

│

├── 📄 data/

│   └── customer_shopping_data.csv

│

├── 🐍 notebooks/

│   ├── data_cleaning_exploration.ipynb

│  

│

├── 🧾 sql_queries

│

├── 📊 powerbi/

│   └── Customer_Shopping_Dashboard.pbix

│

├── 📑 presentation/

│   └── Customer_Shopping_Insights.pptx

│
└── README.md

<h4>📚 Key Learnings</h4>

Complete analytics workflow: Python → SQL → Power BI

Translating transactional data into actionable business strategy.

Using window functions and segmentation logic in SQL for real insights.

Building end-to-end, executive-ready reporting pipelines.

🤝 Connect

📧 Email: sonalipatil2911@gmail.com

🌐 LinkedIn: https://www.linkedin.com/in/sonali-patil-53a48466/

🐙 GitHub: github.com/sonalipatil2911

⭐ If you found this project insightful, please star the repository!
