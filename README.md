# Online Retail Business Analysis

## Project Overview

This project analyzes online retail transaction data to identify sales trends, customer behavior, product performance, and business opportunities.

The analysis combines **Python, SQL, and Power BI** to transform raw transaction data into actionable business insights and an interactive executive dashboard.

### Tools & Technologies

* Python — Data cleaning and exploratory data analysis
* Pandas — Data manipulation and analysis
* SQL — Business queries and KPI analysis
* Power BI — Interactive dashboard and visualization
* Excel — Source dataset

## Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Revenue | £10.06M |
| Total Orders | 19,790 |
| Total Customers | 4,334 |
| Total Units Sold | 5,422,085 |
| Average Order Value | £508.27 |
| Repeat Customers | 2,829 (65.27%) |
| One-time Customers | 1,505 (34.73%) |

## Business Insights

### 1. Strong seasonal sales performance

November 2011 was the strongest month, generating approximately **£1.51M in revenue**.

Insight: Sales increased significantly toward the end of the year, suggesting strong seasonal demand.

> Note: December 2011 contains data only through December 9, so it should not be compared directly with a complete month.

### 2. The UK is the core market

The UK generated approximately **£8.53M in revenue**, making it the largest market by a wide margin.

Insight: The UK is the primary revenue market and should remain a key focus for inventory planning and customer retention.

### 3. Strong customer repeat rate

Approximately **65.27% of customers were repeat customers**, while 34.73% purchased only once.

Insight: The business demonstrates strong customer retention, while the one-time customer segment represents an opportunity for targeted retention campaigns.

### 4. Revenue concentration among high-value customers

The top 10 customers generated approximately **£1.41M**, representing about **14% of total revenue**.

**Insight:** High-value customers contribute meaningfully to overall revenue and could be prioritized through loyalty and retention strategies.

### 5. International markets show high-value opportunities

The Netherlands recorded an average order value of approximately **£3,053**, compared with approximately **£476 in the UK**.

**Insight:** Although some international markets have lower order volumes, their higher average order values may indicate opportunities for targeted international growth.

### 6. Product performance varies significantly

A small group of products generated a substantial share of product revenue, with **REGENCY CAKESTAND 3 TIER** ranking as the highest-revenue product.

**Insight:** High-performing products can be prioritized for inventory availability, promotions, and seasonal merchandising.

## AI-Assisted Business Insights

AI was used as a business analysis assistant to interpret validated findings from Python, SQL, and Power BI.

The AI-assisted analysis helped:

- Interpret key business trends and customer behavior.
- Identify potential business opportunities.
- Translate analytical findings into actionable recommendations.
- Support decision-making based on validated data.

The AI outputs were reviewed against the underlying analytical results to ensure that recommendations were supported by the data.

**Workflow:**

Data → Python EDA → SQL Analysis → Power BI → AI Interpretation → Business Recommendations



## Business Recommendations

Based on the analysis, the following actions could help improve business performance:

1. **Focus on customer retention**
   - Target one-time customers with personalized offers, email campaigns, and loyalty incentives.

2. **Prepare for seasonal demand**
   - Increase inventory and marketing efforts ahead of the November/holiday sales period.

3. **Protect high-value customers**
   - Develop loyalty programs and personalized experiences for customers with consistently high purchase value.

4. **Explore high-value international markets**
   - Investigate markets with high average order values, such as the Netherlands, for targeted expansion.

5. **Prioritize high-performing products**
   - Maintain adequate inventory for top-revenue products and use them in promotional and seasonal campaigns.

6. **Monitor business performance regularly**
   - Use the Power BI dashboard to track revenue, orders, customers, product performance, and customer retention over time.
## Project Workflow

The project followed these main stages:

1. **Data Collection**
   - Used the UCI Online Retail dataset containing retail transaction records.

2. **Data Cleaning**
   - Identified missing values and invalid transaction records.
   - Removed transactions with non-positive unit prices.
   - Separated sales transactions from cancelled transactions.
   - Investigated unusually large quantity values.
   - Excluded operational entries such as postage and manual adjustments from product-level analysis.

3. **Exploratory Data Analysis**
   - Analyzed revenue trends over time.
   - Examined customer purchasing behavior.
   - Identified top-performing products and customers.
   - Compared performance across countries.

4. **SQL Analysis**
   - Created a SQLite database from the cleaned sales data.
   - Used SQL queries to calculate KPIs and analyze customer and country performance.

5. **Power BI Dashboard**
   - Built an interactive executive dashboard.
   - Created KPI cards, revenue trends, product analysis, country analysis, customer analysis, and customer-type segmentation.

6. **Business Insights**
   - Translated analytical findings into business recommendations related to customer retention, seasonal planning, product performance, and international opportunities.
## Power BI Dashboard

   ![Online Retail Business Analysis Dashboard](dashboard.png)

The project includes an executive Power BI dashboard designed to provide a high-level view of retail business performance.

The dashboard includes:

- Total Revenue
- Total Orders
- Total Customers
- Total Units Sold
- Average Order Value
- Monthly Revenue Trend
- Top 10 Countries by Revenue
- Top 10 Products by Revenue
- Top 10 Customers by Revenue
- Customer Type Distribution

The dashboard helps decision-makers quickly identify sales trends, customer behavior, high-performing products, and important markets. 

## Dataset

The project uses the **UCI Online Retail dataset**, which contains transaction-level data from a UK-based online retailer between December 2010 and December 2011.

Source: UCI Machine Learning Repository

## Project Files

| File | Description |
|---|---|
| `Day1_EDA.ipynb` | Python data cleaning and exploratory data analysis |
| `AI_Business_Insights.ipynb` | AI-assisted business insights and recommendations |
| `data/cleaned_sales.csv` | Cleaned sales data used for analysis and Power BI |
| `AI_Business_Analyst.pbix` | Power BI executive dashboard |
| `dashboard.png` | Preview image of the Power BI dashboard |
| `README.md` | Project documentation |

> **Note:** The original Excel dataset and local SQLite database are excluded from the repository. The analysis uses the cleaned `cleaned_sales.csv` file, while the SQLite database can be recreated locally from the cleaned data.
> 
## Skills Demonstrated

- Data Cleaning & Preparation
- Exploratory Data Analysis (EDA)
- Python & Pandas
- SQL
- Power BI
- Data Visualization
- KPI Development
- Customer Segmentation
- Business Analysis
- Business Insights & Recommendations
