# 🚴 Adventure Works - Power BI Business Intelligence & AI Dashboard

An end-to-end Business Intelligence solution built in Power BI Desktop using data from Adventure Works, a fictional global manufacturing company specializing in cycling gear and accessories. 

This project transforms raw transactional data into a fully interactive, 4-page executive dashboard featuring advanced data modeling, dynamic DAX analytics, and AI-driven insights.

---

## 📸 Dashboard Views

* **Executive Dashboard:** High-level KPIs ($24.9M Revenue, $10.5M Profit), revenue trends, monthly KPI variance, and top product performance.
* **Customer Detail:** Demographic breakdowns by income and occupation, top 100 customer leaderboards, and customer lifetime value metrics ($1,431 avg revenue/customer).
* **Product Detail:** Gauge charts for target tracking, dynamic "What-If" price sensitivity parameters, dynamic metric switchers, and AI Smart Narratives.
* **Map View:** Geospatial breakdown across North America, Europe, and Pacific regions.

---

## 🛠️ Tools & Technologies Used

* **Power BI Desktop:** Business intelligence reporting and visual design.
* **Power Query (M):** ETL processes, data cleaning, structural transformations, and column profiling.
* **Data Modeling:** Star Schema design (1-to-many relationships connecting Fact Sales/Returns to Dimension tables for Customers, Products, Territories, and Calendar).
* **DAX (Data Analysis Expressions):** Dynamic measures, time intelligence (`DATESYTD`), context manipulation (`CALCULATE`, `ALL`, `FILTER`), and dynamic numeric parameters.
* **Power BI AI Features:** Native Smart Narrative visuals for automated natural-language data summaries and dynamic key influencer logic.

---

## 💡 Key Business Insights

1. **Volume vs. Profit:** *Accessories* generate the highest order volume, while *Bikes* generate the highest total revenue and profit margins.
2. **Quality Control:** Specific products (e.g., *Sport-100 Helmets*) exhibit return rates above **3.3%**, triggering recommendations for supplier quality checks.
3. **Customer Targeting:** Over 80% of total revenue is driven by customers in *Professional* and *Skilled Manual* occupations, offering clear direction for marketing campaigns.

---

## 📁 Repository Structure

```text
├── Data/                 # Raw CSV files (Sales, Customers, Products, Territories)
├── Screenshots/          # Dashboard report images (Executive, Customer, Product, Map)
├── AdventureWorks.pbix    # Main Power BI project file
└── README.md             # Project documentation
