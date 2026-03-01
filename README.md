# 📊 Vendor Performance Analysis  
### End-to-End Business Intelligence & Data Analytics Project  

---

## 📌 Project Overview  

This project analyzes vendor-level transactional retail data to uncover profitability drivers, pricing inefficiencies, supplier concentration risk, and inventory performance gaps.

The objective was to transform raw sales and procurement data into actionable business insights using Python, statistical validation, and Power BI.

---

## 🎯 Business Problem  

Retail and wholesale businesses must balance:

- Profit margins  
- Inventory turnover  
- Vendor dependency  
- Pricing strategies  

Inefficient pricing, slow-moving inventory, and excessive vendor concentration can significantly impact profitability and working capital efficiency.

This project focuses on:

- Identifying underperforming brands  
- Evaluating vendor contribution concentration  
- Measuring bulk purchasing cost advantages  
- Assessing inventory turnover efficiency  
- Comparing profitability across vendor segments  

---

## 🛠 Tech Stack  

**Programming & Analysis**
- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Jupyter Notebook

**Business Intelligence**
- Power BI
- DAX (KPI modeling, vendor ranking, percentile segmentation)

**Statistical Methods**
- Correlation analysis
- Confidence interval estimation
- Hypothesis testing

**Other Tools**
- Git & GitHub
- LaTeX (Overleaf)

---

## 📊 Key Dashboard Metrics  

- **$441.41M** Total Sales  
- **$307.34M** Total Purchases  
- **$134.07M** Gross Profit  
- **38.72%** Profit Margin  
- **$2.71M** Unsold Inventory Capital  
- **$18.69M** Total Excise Tax  

---

## 🔍 Key Findings  

### Vendor Concentration Risk  
Top 10 vendors contribute **65.69% of total purchases**, indicating supply chain dependency risk.

### High-Margin, Low-Sales Brands  
198 brands show low sales but high margins, presenting opportunities for:
- Pricing optimization  
- Targeted promotions  
- Improved distribution  

### Impact of Bulk Purchasing  
Large order sizes reduce unit purchase cost by **72%**, improving cost efficiency.

### Inventory Inefficiency  
$2.71M in unsold inventory capital tied to slow-moving vendors, impacting working capital.

### Profitability Comparison  

| Vendor Group | Mean Profit Margin | 95% Confidence Interval |
|--------------|-------------------|--------------------------|
| Top Vendors  | 31.17%            | (30.74%, 31.61%)         |
| Low Vendors  | 41.55%            | (40.48%, 42.62%)         |

Statistical testing rejected the null hypothesis, confirming significant differences in profitability models.

---

## 📈 Correlation Insights  

- Purchase Price vs Sales Dollars → Weak correlation (-0.012)  
- Purchase Quantity vs Sales Quantity → Strong correlation (0.999)  
- Profit Margin vs Sales Price → Weak negative relationship (-0.179)  
- Stock Turnover vs Profitability → Weak negative association  

Key insight: High sales volume does not automatically guarantee higher profitability.

---

## 📊 Dashboard Features  

- Executive KPI cards  
- Top vendor purchase contribution visualization  
- Vendor sales ranking  
- Brand performance scatter analysis  
- Low inventory turnover tracking  
- Interactive filtering for dynamic insights  

---

## 💡 Strategic Recommendations  

- Re-evaluate pricing for low-sales, high-margin brands  
- Diversify vendor portfolio to reduce concentration risk  
- Leverage bulk purchasing strategically  
- Optimize slow-moving inventory  
- Strengthen marketing and distribution for underperforming vendors  

---

## 📂 Repository Structure

```text
Vendor Performance VM/
│
├── Vendor_Performance_Analysis_Report.pdf
├── Images/
├── Vendor Performance Analysis.pbix
├── Vendor Performance Analysis.png
│
├── EDA.ipynb
├── Vendor Performance Analysis.ipynb
├── vendor_SQL.ipynb
│
├── get_vendor_summary.py
├── ingestion_db.py
│
├── vendor_sales_summary.csv
├── inventory.db
│
├── logs/
├── venv/
└── data/
```

---

## 🚀 What This Project Demonstrates  

✔ End-to-end data analytics workflow  
✔ KPI-driven business intelligence design  
✔ Statistical validation and hypothesis testing  
✔ Executive dashboard development  
✔ Translation of data into strategic decision-making  

---

## 📬 About  

Viranchi Ravindra More  
MS in Information Systems  

Focused on transforming complex data into measurable business impact.

Open to Data Analyst and Business Intelligence opportunities.
