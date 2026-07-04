# Customer Shopping Behavior Analysis

An end-to-end data analytics project analyzing retail customer shopping behavior using **Python, SQL, and Power BI** — covering data cleaning, business-question-driven SQL analysis, and an interactive dashboard for stakeholder insights.

## 📌 Business Problem

A retail company wants to understand its customers' shopping behavior to improve sales, customer satisfaction, and long-term loyalty. Management has noticed shifts in purchasing patterns across demographics, product categories, and sales channels, and wants to know which factors — discounts, reviews, seasons, or payment preferences — drive consumer decisions and repeat purchases.

**Core question:** *How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?*

## 📁 Project Structure

| File | Description |
|---|---|
| `customer_shopping_behavior.csv` | Raw dataset — customer demographics, purchase details, product info, ratings, subscriptions, shipping, and payment behavior |
| `Customer_Shopping_Behavior_Analysis.ipynb` | Python notebook for data import, exploration, cleaning, and loading into SQL |
| `customer_behavior_sql_queries (1).sql` | SQL queries answering business questions on revenue, discounts, ratings, shipping, subscriptions, and customer segmentation |
| `customer_behavior_dashboard (2).pbix` | Power BI dashboard with interactive visuals on revenue, customer demographics, and spending patterns |
| `Business Problem  Document.pdf` | Business problem statement and project deliverables |
| `Customer Shopping Behavior Analysis.pdf` | Full project report summarizing findings and recommendations |
| `Customer-Shopping-Behavior-Analysis (1).pptx` | Stakeholder presentation deck |
| `LICENSE.txt` | MIT License |

## 🛠️ Workflow

1. **Data Preparation (Python)** — Imported and cleaned the raw CSV dataset (handling data types, missing values, and formatting) in the Jupyter notebook.
2. **Data Analysis (SQL)** — Loaded the cleaned data into a SQL database and wrote queries to answer business questions, including:
   - Revenue by gender
   - Customers who spent above average despite using a discount
   - Top-rated products
   - Standard vs. Express shipping spend comparison
   - Subscriber vs. non-subscriber spend and revenue
   - Products with the highest discount usage
   - Customer segmentation (New / Returning / Loyal) by purchase history
3. **Visualization (Power BI)** — Built an interactive dashboard covering customer count, average purchase amount, review ratings, and subscription trends, with breakdowns by category, age group, gender, and shipping type.
4. **Reporting** — Summarized key findings and business recommendations in a project report and presentation deck.

## 🚀 How to Run This Project

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd customer-shopping-behavior-analysis
   ```
2. **Open the notebook**
   Run `Customer_Shopping_Behavior_Analysis.ipynb` to explore, clean, and prepare the data.
3. **Load into SQL**
   Load the cleaned data into MySQL/PostgreSQL, then run `customer_behavior_sql_queries (1).sql` to answer the business questions.
4. **Explore the dashboard**
   Open `customer_behavior_dashboard (2).pbix` in Power BI Desktop to view and interact with the visuals.
5. **Review the deliverables**
   See the PDF report and PPTX presentation for the summarized findings and recommendations.

## 🧰 Tech Stack

- **Python** — Pandas, data cleaning & preparation
- **SQL** — PostgreSQL-style queries (CTEs, aggregations, window-style segmentation)
- **Power BI** — DAX, data modeling, interactive dashboard design

## 📜 License

MIT — see `LICENSE.txt` for details.

## 👤 Author

Sudarshan Pulgamwar
📧 sudarshanpulgamwar07@gmail.com
🔗 [GitHub](https://github.com/sudershanlp9-crypto)