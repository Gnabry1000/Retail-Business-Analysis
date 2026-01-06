# Retail Business Analysis

A comprehensive data analysis project using Python and Pandas to explore and derive insights from online retail sales data. This project analyzes customer behavior, revenue trends, product popularity, and more for a UK-based online retail store.

## Features

- **Data Cleaning**: Handles missing values, removes invalid transactions, and prepares data for analysis.
- **Exploratory Data Analysis (EDA)**: Includes visualizations of sales trends, top products, and customer distributions.
- **Revenue Analysis**: Examines revenue by time periods, countries, and customer segments.
- **Customer Segmentation**: Implements RFM (Recency, Frequency, Monetary) analysis to categorize customers.
- **Cohort Analysis**: Tracks customer retention and behavior over time.
- **Product Insights**: Identifies frequently bought-together products and top-selling items.
- **Key Metrics**: Calculates average order value, customer lifetime value, and other business KPIs.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Retail_Business_Analysis.git
   cd Retail_Business_Analysis
   ```

2. Install required dependencies:
   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```

3. Ensure the data file `data/online_retail_II.csv` is present in the `data/` directory.

## Usage

1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Open `Business_Analysis.ipynb` and run the cells sequentially to execute the analysis.

3. View the generated visualizations and outputs within the notebook.

## Data

The analysis uses the "Online Retail II" dataset from the UCI Machine Learning Repository, containing transactions from a UK-based online retail store between 2009-2011. The dataset includes fields like InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, and Country.

- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/502/online+retail+ii)
- File: `data/online_retail_II.csv`

## Dependencies

- Python 3.x
- pandas
- matplotlib
- seaborn
- jupyter (for running the notebook)

## License

This project is for educational purposes. Please refer to the data source for any licensing information.

## Author

Nkonzo Tshabangu

