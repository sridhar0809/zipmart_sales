# 🛒 ZipMart — Sales Intelligence Pipeline

An **automated ETL pipeline** that processes and analyzes e-commerce sales data from multiple sources (CSV and JSON) using Python and Pandas. This project demonstrates end-to-end data engineering with a focus on data cleaning, transformation, and business reporting.

---

## 📌 Project Overview

ZipMart simulates a real-world e-commerce data pipeline. It ingests raw sales data, cleans and transforms it, integrates multiple datasets, and generates actionable business insights like revenue analysis, top-selling products, and city-wise sales trends.

---

## 🏗️ Pipeline Architecture

```
Raw Data (CSV + JSON)
        ↓
   Extraction       →  Load data from multiple file sources
        ↓
   Transformation   →  Clean, deduplicate, integrate datasets
        ↓
   Analysis         →  Revenue, products, categories, cities
        ↓
   Reporting        →  Business insight reports
```

---

## ⚙️ Key Features

- ✅ **Multi-source Ingestion** — Reads CSV and JSON files
- ✅ **Data Cleaning** — Handles nulls, duplicates, and invalid records
- ✅ **Dataset Integration** — Merges sales, product, and customer data
- ✅ **Revenue Calculations** — Computes totals, averages, and growth
- ✅ **Modular Functions** — Reusable extract, transform, load modules
- ✅ **Business Insights:**
  - 💰 Total and category-wise revenue analysis
  - 🏆 Top-selling products ranking
  - 🏙️ City-wise sales performance
  - 📈 Monthly sales trend reports

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data manipulation & analysis |
| CSV / JSON | Input data formats |
| ETL | Extract, Transform, Load pipeline |

---

## 📁 Project Structure

```
zipmart-sales-pipeline/
│
├── data/
│   ├── sales_data.csv              # Raw sales data
│   └── product_data.json           # Product information
├── etl/
│   ├── extract.py                  # Data extraction functions
│   ├── transform.py                # Cleaning & transformation
│   └── load.py                     # Output & reporting
├── analysis/
│   ├── revenue_analysis.py         # Revenue insights
│   ├── product_performance.py      # Top products report
│   └── city_sales_trends.py        # City-wise analysis
├── reports/
│   └── sales_report.csv            # Generated output report
├── main.py                         # Main pipeline runner
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/zipmart-sales-pipeline.git
   ```

2. Install dependencies:
   ```bash
   pip install pandas
   ```

3. Add your data files to the `data/` folder

4. Run the pipeline:
   ```bash
   python main.py
   ```

5. View generated reports in the `reports/` folder

---

## 📊 Sample Insights Generated

- Top 10 best-selling products
- Revenue by product category
- City-wise total sales ranking
- Monthly revenue growth trend

---

## 👤 Author

**Sridharsudhakar**
📧 sridharZ14309@gmail.com
📞 +91 8015249830
