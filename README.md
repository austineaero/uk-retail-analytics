# UK Retail Data Analytics with Databricks

End‑to‑end analytics demo using public dataset: *UCI Online Retail (UK transactions, 2010‑2011)*.

---

## Project Structure

```
uk-data-analytics/
├── notebooks/
│   ├── 00_download_data.ipynb      # Download the Excel dataset and save as CSV
│   ├── 01_clean_transform.ipynb    # Clean and prepare the data for analysis
│   ├── 02_analysis_visuals.ipynb   # Explore business insights and create charts
│   └── 03_export_dashboard.ipynb   # Export summary tables and charts for dashboards
├── data/                           # All CSV files created by the notebooks
├── dashboard/                      # Chart images and screenshots of outputs
├── requirements.txt                # List of required Python packages
└── README.md                       # Project overview and instructions
```

---

## Quick Start (Databricks, Jupyter, or VS Code)

1. **Clone or download** the repo, then run
   `pip install -r requirements.txt`
   *(Only once per environment! No need to pip install in every notebook cell.)*

2. **Open the notebooks in order:**

   * **00\_download\_data.ipynb**: Downloads the Excel dataset and saves it as `data/online_retail.csv`.
   * **01\_clean\_transform.ipynb**: Loads the CSV, cleans the data, and adds calculated fields.
   * **02\_analysis\_visuals.ipynb**: Generates monthly sales trends, top products, and top countries charts; saves PNGs to `dashboard/`.
   * **03\_export\_dashboard.ipynb**: Writes summary CSVs for dashboards (e.g., `monthly_sales.csv`, `top_products.csv`).

3. **To present/share your findings:**

   * Open any chart images in the `dashboard/` folder.
   * Optionally, import the exported CSVs into Power BI or Tableau and build additional visuals, saving screenshots to the same folder.

---

## Why this project?

* Demonstrates real-world data engineering and analytics in one seamless workflow.
* Uses open UK retail data for the analysis.