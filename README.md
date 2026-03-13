# 📊 SalesCaptain: Data Analyzer & Visualization

A powerful Python-based data analysis tool that integrates **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**. This utility is designed to streamline the workflow of loading, cleaning, analyzing, and visualizing sales datasets. It even includes a synthetic data generator if no CSV is provided, making it perfect for immediate demonstrations.

---

## 🌟 Core Features

* **Smart Data Loading:** Automatically detects and parses date columns or generates a synthetic 12-month dataset if the source file is missing.
* **Automated Data Repair:** * Removes duplicate records.
* Fills missing categorical data with the most frequent value (mode).
* Imputes missing numerical values using the column mean.


* **Advanced Analytics:** * **Grouped Aggregations:** View Sum, Mean, and Count of Sales/Profit by Region.
* **Deep Statistics:** Calculates Standard Deviation, Variance, and 25th Percentile Quantiles.
* **Pivot Tables:** Generate custom Product vs. Region sales matrices.


* **Numerical Processing:** Uses NumPy for high-performance array slicing, indexing, and vector operations (e.g., bulk doubling of sales figures).
* **Automated Visualization:** Generates and saves high-quality charts:
* **Bar Chart:** Total Sales by Product.
* **Scatter Plot:** Relationship between Sales and Profit.
* **Box Plot:** Distribution and outlier detection for Sales and Profit.



---

## 🛠️ Technical Stack

| Library | Usage in `8_Analyzer.py` |
| --- | --- |
| **Pandas** | DataFrames, CSV I/O, GroupBy, Pivot Tables, and Cleaning. |
| **NumPy** | Array conversions, statistical calculations, and vector math. |
| **Matplotlib** | Core plotting engine for bar and scatter charts. |
| **Seaborn** | Advanced statistical visualization for box plots. |

---


2. **Load Data (Option 1):** Provide a path to your CSV or press enter to generate `sales_6.csv` automatically.
3. **Clean & Repair (Option 3):** Run the repair function to handle any `NaN` values or duplicates.
4. **Analyze (Options 5-7):** Explore regional totals, deep statistics, or pivot your data for a different perspective.
5. **Visualize (Option 8):** Generate PNG plots directly in your project folder.

---

## 📋 Requirements

* Python 3.x
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`

---

## 👤 Author

**Aesha makrubiya**

---
