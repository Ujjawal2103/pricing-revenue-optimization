# Retail Pricing & Revenue Optimization Analytics

## Project Overview

This project analyzes retail sales data to support pricing and revenue optimization using Python-based data analytics. It focuses on understanding customer price sensitivity, identifying high-value products, comparing product prices with competitors, and evaluating inventory levels to support better business decisions.

The project generates a synthetic retail dataset and performs multiple analyses that help estimate the impact of pricing strategies on revenue and product performance.

---

## Objectives

- Generate a realistic retail sales dataset for analysis.
- Analyze customer demand using price elasticity.
- Identify high-revenue products using Pareto (ABC) segmentation.
- Compare product pricing with market competitors.
- Assess inventory sufficiency for different products.
- Simulate revenue under different pricing scenarios.

---

## Project Structure

```text
Pricing-Revenue-Optimization/
│
├── data/
│   ├── sales_data.csv
│   ├── processed_sales_data.csv
│   ├── sku_segmentation.csv
│   ├── sku_elasticity.csv
│   ├── revenue_simulation.csv
│   ├── competitor_data.csv
│   ├── competitor_analysis.csv
│   └── inventory_sufficiency.csv
│
├── scripts/
│   ├── generate_data.py
│   ├── analyze_segments.py
│   ├── analyze_elasticity.py
│   └── analyze_market_inventory.py
│
└── README.md
```

---

## Features

### Price Elasticity Analysis
Measures how changes in product prices influence customer demand and estimates the effect of pricing decisions on revenue.

### SKU Segmentation
Uses Pareto (ABC) analysis to classify products based on their contribution to overall revenue and identify high-performing SKUs.

### Revenue Simulation
Evaluates different pricing scenarios and estimates their potential impact on total revenue.

### Competitor Price Analysis
Compares internal product prices with competitor pricing to understand market positioning.

### Inventory Analysis
Evaluates inventory sufficiency and identifies products that may require replenishment or pricing adjustments.

---

## Getting Started

### Prerequisites

- Python 3.11 or later
- Required Python libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scipy
  - statsmodels

Install the required packages:

```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels
```

---

## Running the Project

Execute the scripts in the following order:

```bash
python scripts/generate_data.py
python scripts/analyze_segments.py
python scripts/analyze_elasticity.py
python scripts/analyze_market_inventory.py
```

The generated datasets and analysis results will be saved inside the **data/** directory.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels

---

## Business Insights Generated

This project helps answer business questions such as:

- Which products contribute the most to total revenue?
- Which products are highly sensitive to price changes?
- How do our prices compare with competitors?
- Which products require inventory attention?
- How can pricing changes affect future revenue?

---

## Future Improvements

- Build an interactive Power BI dashboard for business reporting.
- Add forecasting models for future sales prediction.
- Connect the project to a SQL database instead of CSV files.
- Extend the pricing simulation with additional business constraints.