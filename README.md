# 🌍 Global Super Store — Executive Insights Dashboard
**Tool:** Tableau Desktop Public Edition  
**Dataset:** Global Superstore 2018 (Orders table — 51,290 rows, 24 fields)  
**Author:** Shiny Madona Arockiasamy

---

## 📌 Project Overview

This project analyses 5+ years of global retail data from the Global Superstore dataset to uncover sales trends, profitability patterns, and operational insights across product categories, geographies, and customer segments.

The final output is a multi-view **Executive Insights Dashboard** combining 5 interactive worksheets into a single decision-ready view for business stakeholders.

---

## 🎯 Business Questions Answered

1. How are sales trending across product categories, and what does the forecast look like?
2. Which countries contribute the most to total sales globally?
3. Which sub-categories are most and least profitable?
4. Are high-sales products always high-profit? Where are the outliers?
5. How are orders distributed across priority levels?

---

## 📊 Dashboard Views

### 1. Executive Insights Dashboard
A consolidated single-screen view combining all 5 worksheets for leadership reporting.

![Executive Insights Dashboard](dashboard_screenshots/Dashboard.png)

---

### 2. Sales Forecasted by Category
Time series analysis of monthly sales from October 2013 to early 2019 across Furniture, Office Supplies, and Technology — with Tableau's built-in forecast showing projected trend bands.

**Key Insight:** All three categories show consistent upward growth. Technology shows the steepest acceleration from 2017 onwards, suggesting increasing market demand.

![Sales Forecasted by Category](dashboard_screenshots/Sales_Forecasted_by_Category_.png)

---

### 3. Total Sales by Each Country
A filled map showing % share of total sales by country across 165 markets.

**Key Insight:** The United States dominates with 18.17% of global sales, followed by Australia (7.32%), China (5.54%), and Mexico (4.92%). Large portions of Africa and Central Asia show near-zero contribution — potential untapped markets.

![Total Sales by Each Country](dashboard_screenshots/Total_Sales_by_Each_Country.png)

---

### 4. Profit Distribution for Each Category
A treemap sized by Sales and coloured by Profit across all sub-categories within Furniture, Office Supplies, and Technology.

**Key Insight:** Technology Copiers and Technology Phones are the largest revenue generators. However, several Furniture sub-categories (Bookcases, Chairs) show darker red colouring, indicating high sales volume paired with low or negative profit margins — a classic over-discounting signal.

![Profit Distribution for Each Category](dashboard_screenshots/Profit_Distribution_for_Each_Category.png)

---

### 5. Profit vs Sales for Each Product
A scatter plot of 3,788 individual products mapping Sales (Y-axis) against Profit (X-axis).

**Key Insight:** The majority of products cluster near zero profit despite moderate sales — suggesting margin leakage at the product level. A small number of outlier products drive disproportionately high profit at high sales volumes. Products in the negative profit zone (left of zero) are loss-makers worth investigating.

![Profit vs Sales for Each Product](dashboard_screenshots/Profit_vs_Sales_for_Each_Product_.png)

---

### 6. Order Priority Distribution
A pie chart showing the distribution of 51,290 orders across four priority levels.

**Key Insight:** 57.39% of all orders are Medium priority, with High at 30.22%. Critical orders account for only 7.67% — indicating most fulfillment pressure falls in the medium band, which may affect SLA planning.

![Order Priority Distribution](dashboard_screenshots/Order_Priority_Distribution.png)

---

## 🔑 Key Findings Summary

| Finding | Detail |
|---|---|
| Top market | United States — 18.17% of global sales |
| Fastest growing category | Technology (steepest upward trend 2017–2019) |
| Profit risk area | Furniture sub-categories — high sales, low/negative margins |
| Product-level concern | Large cluster of products with near-zero profit despite positive sales |
| Order volume | 57% Medium priority — operational planning implication |

---

## 🗂️ Data Source

- **Dataset:** Global Superstore 2018
- **Source:** [Kaggle — Global Superstore Dataset](https://www.kaggle.com/datasets/apoorvaappz/global-super-store-dataset)
- **Table used:** Orders (51,290 rows, 24 fields)
- **Fields include:** Order ID, Order Date, Ship Date, Ship Mode, Customer Segment, Country, Category, Sub-Category, Sales, Quantity, Discount, Profit, Shipping Cost, Order Priority

---

## 🛠️ Tools Used

- Tableau Desktop Public Edition
- Microsoft Excel (data source)

---

## 📁 Repository Structure

```
tableau-global-superstore/
├── README.md
├── dashboard_screenshots/
│   ├── Dashboard.png
│   ├── Sales_Forecasted_by_Category_.png
│   ├── Total_Sales_by_Each_Country.png
│   ├── Profit_Distribution_for_Each_Category.png
│   ├── Profit_vs_Sales_for_Each_Product_.png
│   └── Order_Priority_Distribution.png
└── data/
    └── source_note.md        ← link to Kaggle dataset
```

---

## 👩‍💻 About

**Shiny Madona Arockiasamy**  
IBM Certified Data Analyst | Tableau | Power BI | Python | SQL  
[LinkedIn](#) · [Portfolio](#) · shinymadona@gmail.com
