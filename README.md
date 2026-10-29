# 🛒 E-Commerce Sales Analysis | Python, SQL, Excel & Power BI

An end-to-end data analytics project focused on cleaning e-commerce data, analyzing sales and profitability, identifying business trends, and presenting insights through an interactive Power BI dashboard.

## 📌 Project Overview

The objective of this project is to transform raw e-commerce data into meaningful business insights. The project involves data cleaning, data preparation, exploratory data analysis, sales and profit calculations, and interactive dashboard development.

The analysis helps understand sales performance, product profitability, category contribution, regional performance, and order trends.

## 🎯 Business Objectives

- Clean and prepare raw e-commerce data for analysis.
- Identify and handle missing values, duplicates, and inconsistent data.
- Calculate key sales and profitability metrics.
- Analyze sales performance across product categories and cities.
- Identify top-performing products and categories.
- Understand monthly sales trends.
- Build an interactive Power BI dashboard to communicate insights.
- Support data-driven business decisions.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data cleaning, preprocessing, and analysis |
| Pandas | Data manipulation and transformation |
| NumPy | Numerical calculations |
| Jupyter Notebook | Executing and documenting the analysis |
| Microsoft Excel | Dataset inspection and spreadsheet operations |
| MySQL / SQL | Database querying and data analysis, where configured |
| Microsoft Power BI | Interactive dashboard and visualization |

## 📂 Project Structure

```text
Ecommerce-Sales-Analysis/
│
├── data/
│   ├── Ecommerce_Unclean_Project.xlsx
│   └── Cleaned_ecommerce.xls
│
├── notebooks/
│   └── Ecommerce_analysis.ipynb
│
├── dashboard/
│   └── ecommerce-powerbi.pbix
│
├── screenshots/
│   └── dashboard-overview.png
│
├── README.md
└── .gitignore
```

*Note: The structure above is the recommended organization. Update the paths if your repository uses a different folder structure.*

## 📊 Dataset Information

The project uses an e-commerce dataset containing transaction and order-related information.

- Raw dataset: `Ecommerce_Unclean_Project.xlsx`
- Processed dataset: `Cleaned_ecommerce.xls`
- Reported cleaned dataset size: approximately 380 records
- Reported distinct orders: 374

The data is prepared for sales analysis and dashboard reporting.

## 🔄 Project Workflow

### 1. Data Collection
- Load the raw e-commerce dataset.
- Inspect the dataset structure, columns, data types, and dimensions.
- Understand the available sales, product, category, location, and order information.

### 2. Data Cleaning & Preprocessing
- Inspect missing and duplicate values.
- Standardize inconsistent text values.
- Convert columns to appropriate data types.
- Prepare date and numerical fields for analysis.
- Export the processed dataset for further analysis and visualization.

### 3. Exploratory Data Analysis
Analyze the prepared data to understand:

- Overall sales performance.
- Sales by city and category.
- Product-level profit contribution.
- Monthly sales trends.
- Order status distribution.
- Differences in performance across business segments.

### 4. Feature Engineering & Calculations
Prepare analytical metrics such as:

- Total Sales
- Total Profit
- Distinct Orders
- Category-wise Sales
- City-wise Sales
- Product-wise Profit
- Monthly Sales

**Profit calculation note:** If profit is calculated as 20% of net sales in the notebook, it represents an estimated profit based on an assumed margin, not verified actual business profit.

### 5. Power BI Dashboard
Develop an interactive dashboard to summarize important business metrics and trends.

The dashboard includes KPI cards, monthly sales trends, city-level sales comparisons, category contribution, and product-level profit comparisons.

### 6. Business Insights
Use the analysis to identify strong-performing categories, high-sales cities, and products contributing to the calculated profit metric.

## 📈 Key Dashboard Results

The following figures are based on the current dashboard and should be interpreted according to the dataset's calculation assumptions.

| KPI / Metric | Reported Result |
|---|---:|
| Total Sales | 3.52M |
| Calculated Profit | 703.09K |
| Distinct Orders | 374 |
| Cleaned Dataset Records | 380 |
| Electronics Sales | 1.33M |
| Electronics Calculated Profit | 266.05K |
| Electronics Share of Calculated Profit | 37.84% |

### Key Findings

- **Electronics:** The category contributes approximately 1.33M in sales and 266.05K in calculated profit.
- **Category contribution:** Electronics accounts for approximately 37.84% of the displayed total calculated profit.
- **Regional performance:** Pune and Bengaluru are among the higher-sales cities in the dashboard.
- **Product performance:** Laptops and chairs are among the products with the highest displayed profit values.
- **Monthly trends:** The dashboard compares sales from January through June to identify changes in performance.

*Important:* The dashboard's displayed values depend on the dataset and calculation logic. Profit figures should be described as estimates wherever the 20% assumed margin is used. Validate the metrics before using them in business decisions or resume claims.

## 📊 Dashboard Preview

The Power BI report provides a visual overview of:

- Sales and profit KPIs
- Monthly sales trends
- City-wise sales performance
- Category-wise sales contribution
- Product-wise calculated profit
- Order-related analysis

To view the dashboard, open `ecommerce-powerbi.pbix` using Microsoft Power BI Desktop.

If a dashboard screenshot is available, place it in the `screenshots/` folder and add it here:

```markdown
![E-Commerce Sales Dashboard](screenshots/dashboard-overview.png)
```

## 🚀 How to Run the Project

### Prerequisites

Install the following software as needed:

- Python 3.11 or another compatible version
- Jupyter Notebook
- Microsoft Excel
- Microsoft Power BI Desktop
- MySQL Server and MySQL client, if using the database integration

### Step 1: Clone the Repository

```bash
git clone https://github.com/Neeraj472/Ecommerce-Sales-Analysis.git
```

### Step 2: Open the Project

```bash
cd Ecommerce-Sales-Analysis
```

### Step 3: Create a Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### Step 4: Install Python Libraries

```bash
pip install pandas numpy openpyxl xlrd jupyter notebook
```

Install any additional libraries required by the notebook.

### Step 5: Run the Notebook

```bash
jupyter notebook
```

Open `Ecommerce_analysis.ipynb` and execute the cells in order. Update dataset paths if necessary.

### Step 6: Open the Power BI Dashboard

Open `ecommerce-powerbi.pbix` in Power BI Desktop and refresh the data source if required. Update file paths or database connection settings to match your environment.

### Optional: MySQL Integration

If the notebook includes working MySQL integration, configure your database connection, create or select the required database, and execute the SQL-related cells. Database credentials must be supplied securely rather than hardcoded in the notebook.

## 💼 Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Data manipulation with Pandas and NumPy
- Sales and profitability analysis
- Business KPI reporting
- Data visualization
- Power BI dashboard development
- SQL and database integration, where implemented and tested
- Analytical thinking and business insight generation

## 🔮 Future Improvements

- Correct and validate the profit calculation using actual cost and revenue data.
- Add a verified average order value measure.
- Improve data validation and automated data-cleaning checks.
- Add more detailed customer segmentation and retention analysis.
- Include time-based comparisons and additional business KPIs.
- Improve dashboard filtering and drill-through functionality.
- Automate the data refresh process.
- Add a documented SQL analysis section with reproducible queries.

## 👨‍💻 Author

**Neeraj Kumar**

B.Tech — Computer Science Engineering (AI & ML)

GitHub: [Neeraj472](https://github.com/Neeraj472)

## ⭐ Support

If you find this project useful, consider giving the repository a star ⭐.

Feedback and suggestions for improving the analysis are welcome.

---

*This project is intended for educational and portfolio purposes. Reported business metrics depend on the dataset and the assumptions used in the calculations.*
