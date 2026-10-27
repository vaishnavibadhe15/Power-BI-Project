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

## 1.Exec Dashboard
<img width="1292" height="732" alt="image" src="https://github.com/user-attachments/assets/a57f8a70-16cb-412f-8736-08bbce959e09" />

## 2.Map
<img width="1193" height="691" alt="image" src="https://github.com/user-attachments/assets/0cd31efe-5017-46ed-ac91-a6ea76526f51" />

## 3.Product Detail
<img width="1290" height="712" alt="image" src="https://github.com/user-attachments/assets/3785eb50-7345-4e52-9d63-137763a67429" />

## 4.Customer Detail
<img width="1285" height="781" alt="image" src="https://github.com/user-attachments/assets/6c8dd14f-900b-4210-8c40-b076da929488" />

## 5.Category Tooltip
<img width="530" height="278" alt="image" src="https://github.com/user-attachments/assets/5ab69129-f093-4b6a-9b5c-feea81d0e63b" />

## 6.Q&A
<img width="1257" height="700" alt="image" src="https://github.com/user-attachments/assets/9b325136-b9be-4a49-a9c0-ecc919df4f0b" />

## 7.Decomposition Tree
<img width="1268" height="708" alt="image" src="https://github.com/user-attachments/assets/b2beb9b1-b168-40d0-8de2-be26217c3b38" />

## 8.Key Influencers
<img width="1258" height="662" alt="image" src="https://github.com/user-attachments/assets/8920d374-1339-4d52-a4dc-7e17ce3735c2" />



---

## Key Insights

1. **Strong growth with a step change in mid-2021.** Monthly revenue grew from about $0.6M in early 2020 to **$1.83M** in the latest month (+3.3% vs. the previous month). Monthly orders roughly tripled between Jul and Aug 2021 (about 500 to about 1,500) and stayed at the higher level, which points to a structural change in the business (for example a product launch or new channel) worth investigating.
2. **Healthy profitability.** **$24.9M revenue** and **$10.5M profit** from **25.2K orders** is a profit margin of about **42%**, with an overall return rate of just **2.2%**.
3. **Accessories drive order volume.** Accessories lead with 17.0K orders, ahead of Bikes (13.9K) and Clothing (7.0K). Within Accessories, Tires and Tubes is the largest subcategory (9,084 orders), and the Water Bottle (30 oz) is the single most-ordered product (3,983 orders).
4. **Helmets have above-average returns.** Sport-100 Helmets show return rates of 3.33% (Red), 3.31% (Blue) and 2.68% (Black) against 2.2% overall, and Shorts are the most-returned product type.
5. **Sales are concentrated in a few markets.** The United States and Australia are the largest markets on the map, followed by Canada, the UK, France and Germany.
6. **Customers buy rarely, but revenue is not dependent on a few buyers.** 17.4K unique customers generate **$1,431 revenue per customer**, which works out to roughly 1.45 orders per customer. The top 100 customers contribute only about $615K (around 2.5% of total revenue), so revenue is spread widely.
7. **Customer profile.** Average-income customers place the most orders (11.6K), followed by low-income (10.3K) and high-income (2.8K) customers. Professionals are the largest occupation group (7.9K orders), followed by Skilled Manual (6.0K) and Management (4.4K).
8. **Product targets.** For the Water Bottle (30 oz), the latest month reached 404 orders vs. a 438 target (92%), $4,067 revenue vs. $4,292 (95%), and $2,546 profit vs. $2,687 (95%), so it is slightly below target on all three.
9. **Key Influencers (exploratory).** Married customers are 1.62x and parents 1.59x more likely to be homeowners, and average retail price rises with product cost, as expected.

### Recommendations

- **Build repeat-purchase programs** (loyalty offers, follow-up emails, bundles), since most customers order only about once.
- **Investigate Sport-100 Helmet returns** (quality, sizing, product description) to bring them down to the 2.2% average.
- **Cross-sell accessories with bikes**, because accessories already have the highest order volume and profit margins are strong enough to support bundles.
- **Explore growth in smaller markets** (UK, France, Germany, Canada) with targeted campaigns.

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

**Vaishnavi Badhe**

Data Analyst | Python, SQL, Power BI, Machine Learning
Mumbai, India

