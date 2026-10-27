# AdventureWorks Sales Analytics Dashboard (Power BI)

An interactive, multi-page Power BI report analysing sales, products, and customers for AdventureWorks, a fictional bicycle manufacturer. The report covers executive-level KPIs, geographic performance, product and customer deep-dives, and AI-powered visuals for finding what drives sales.


<img width="1321" height="742" alt="image" src="https://github.com/user-attachments/assets/f1a26d24-3a9f-4b03-82d7-ad82b2b24a53" />

---

## Business Questions Answered

- How are revenue, profit, and orders trending over time?
- Which regions and countries drive the most sales?
- Which products and categories perform best, and against what targets?
- Who are our customers, and which segments contribute most revenue?
- What factors influence sales the most?

---

## Report Pages

| Page | What it shows |
|------|---------------|
| **Exec Dashboard** | Headline KPI cards, revenue trend (line chart), category comparison (bar chart), summary pivot table, year/region slicers, and navigation buttons |
| **Map** | Geographic view of sales by location, filterable with slicers |
| **Product Detail** | Gauges for performance vs. targets, trend and area charts, product slicers |
| **Customer Detail** | Customer KPIs, revenue split by segment (donut charts), customer table, trend line |
| **Category Tooltip** | Custom tooltip page that appears on hover over category visuals |
| **Q&A** | Natural-language question box so users can query the data by typing |
| **Decomposition Tree** | Drill into a metric across dimensions to find where the numbers come from |
| **Key Influencers** | AI visual that ranks the factors driving a chosen outcome |

*(Add a screenshot for each page in the `images/` folder and link them here.)*

---

## Key Insights

> Replace these with your real findings. Recruiters read this section first.

1. **[Insight 1]**: e.g., "Bikes generate X% of total revenue, but Accessories have the highest profit margin."
2. **[Insight 2]**: e.g., "Sales peaked in [month/year]; [region] grew X% year over year."
3. **[Insight 3]**: e.g., "Top N% of customers account for X% of revenue."
4. **[Recommendation]**: What would you suggest the business do based on this?

---

## Features and Techniques Used

- Multi-page report design with consistent layout and **button-based navigation**
- **Slicers** and cross-filtering for interactive exploration
- **KPI cards, gauges, line/area/bar/donut charts, maps, pivot tables**
- **Custom tooltip page** (report-page tooltip)
- **AI visuals**: Q&A, Decomposition Tree, Key Influencers
- **Data model** with relationships between fact and dimension tables (star schema)
- **DAX measures**: [list a few, e.g., Total Sales, Profit Margin %, YoY Growth, Running Total]
- **Power Query** transformations: [e.g., cleaned columns, changed data types, merged tables]

---

## Tools

- Power BI Desktop
- DAX
- Power Query (M)
- Dataset: Microsoft AdventureWorks sample data

---

## How to Open This Report

1. Download **AdventureWorks_Report_FINAL.pbix** from this repository.
2. Open it in **Power BI Desktop** (free; Windows only).
3. Use the slicers and navigation buttons to explore each page.

---

## Repository Structure

```
├── AdventureWorks_Report_FINAL.pbix   # Power BI report
├── README.md
├── images/                            # Screenshots of each report page
├── docs/
│   └── AdventureWorks_Report.pdf      # PDF export for quick viewing
└── dax/
    └── measures.md                    # Key DAX measures with explanations
```

---

## Author

**Javed Shaikh**
Data Scientist / Mentor | Python, SQL, Power BI, Machine Learning
Pune, India

- LinkedIn: [your-link]
- GitHub: [your-link]
- Email: [your-email]
- Portfolio: [your-link, optional]
