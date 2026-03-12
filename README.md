
---

## 📊 Amazon Sales Analysis Dashboard

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
</p>

An interactive **Power BI dashboard** analyzing Amazon sales data to uncover revenue trends, category performance, and profitability insights.

---

### 🎯 Project Overview

This project transforms raw Amazon sales data into actionable business intelligence through:
- **Revenue trend analysis** across states and time periods
- **Category-wise performance** breakdown
- **Profitability metrics** (Revenue, Cost, Net Profit, ROI)
- **Cancellation analysis** to identify operational issues

---

### 📁 Repository Structure

```
amazon-sales-analysis/
├── 📂 data/
│   ├── raw_sales_data.csv          # Original dataset
│   └── cleaned_sales_data.csv      # Processed data
├── 📂 dashboard/
│   ├── amazon_sales_dashboard.pbix # Power BI file
│   └── dashboard_screenshots/      # PNG exports
├── 📂 scripts/
│   ├── data_cleaning.py            # Python preprocessing
│   └── kpi_calculations.py         # Metric computations
├── 📂 docs/
│   └── project_report.pdf          # Detailed analysis
└── README.md                       # This file
```

---

### 🚀 Key Features

| Feature | Description |
|---------|-------------|
| **Sales Revenue by State** | Time-series line graph showing geographic revenue trends |
| **Sales by Category** | Comparative bar chart for product performance |
| **KPI Cards** | Real-time metrics: Total Revenue, Cost, Net Profit, ROI |
| **Cancelled Orders** | Funnel chart highlighting cancellation rates by category |
| **Revenue/Cost/Profit** | Stacked bar chart for financial breakdown by ship-state |
| **Interactive Filtering** | Filter by date, category, and state |
| **Export Options** | Download reports as CSV or PDF |

---


### 🛠️ Tech Stack

- **Power BI** – Data visualization & interactive dashboards
- **Python (Pandas)** – Data cleaning & preprocessing
- **Excel** – Initial data exploration
- **DAX** – Calculated measures & KPIs

---

### ⚡ Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/amazon-sales-analysis.git
   cd amazon-sales-analysis
   ```

2. **Open the dashboard**
   - Download `dashboard/amazon_sales_dashboard.pbix`
   - Open with **Power BI Desktop**

3. **View the data**
   - Check `data/cleaned_sales_data.csv` for processed dataset

---


### 🤝 Contributing

Contributions welcome! If you'd like to improve the dashboard or add new analyses:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-analysis`)
3. Commit changes (`git commit -m 'Add new visualization'`)
4. Push to branch (`git push origin feature/new-analysis`)
5. Open a Pull Request

---

### 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

