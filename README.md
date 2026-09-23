#  Fitbit Sales & Marketing Performance Dashboard (Power BI)

An interactive Power BI dashboard designed to track, analyze, and optimize marketing campaigns and sales performance for Fitbit products. This project transforms raw advertising and sales data into actionable business insights.

---

##  Live Preview / Screenshots

### 1. Overview Page
- **Metrics Tracked:** Total Impressions (48K), Click-Through Rate (10%), Total Conversions (1K), Conversion Rate (31%), Total Clicks (5K), and Total Sales ($411K).
- **Ad Platform Breakdown:** Visualizes performance across Google, Facebook, Instagram, and X.

### 2. Analysis Page
- **Demographic Insights:** Breakdown of sales by gender (Female: 33.93%, Male: 30.81%, Other: 35.25%).
- **Quarterly Trends:** Evaluates Average Order Value (AOV) and Total Conversions across Qtr 1 to Qtr 4.

---

##  Key Features & Capabilities

- **Interactive Filtering (Slicers):** Dynamic filters for Gender, Month, Product Category, and Hour Group to allow deep exploratory data analysis.
- **Multi-Platform Marketing Analysis:** Evaluates which ad platforms drive the most traffic, clicks, and revenue.
- **Financial & Conversion Tracking:** Links marketing metrics directly to bottom-line sales and average order values ($275 AOV).
- **Clean UI/UX Design:** Built with a modern dark-blue theme, structured layout, navigation buttons (Home, Overview, Analysis), and clear KPI cards.

---

Tools & Technologies Used
Microsoft Power BI: Data modeling, DAX measures, interactive reporting, and UI design.

Power Query: Data cleaning and transformation.

Excel / CSV: Initial data source handling.

 Key Business Insights Discovered
Top Ad Platforms: Google and Facebook lead in total sales generation compared to Instagram and X.

Conversion Optimization: Despite high impression volumes, conversion rates highlight areas for funnel optimization.

Seasonal Trends: Quarterly fluctuations in AOV help forecast high-performing sales periods.

##  Project Structure

```text
├── Dashboard/
│   ├── fitbit_dashboard.pbix   # The main Power BI file
│   └── screenshots/            # Dashboard preview images
├── Data/
│   └── raw_data.csv            # Cleaned dataset used for the project
└── README.md                   # Project documentation
