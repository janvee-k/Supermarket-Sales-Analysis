# Supermarket Sales Analysis

This project presents a full-scale sales analysis using both Python (Jupyter Notebook) and Power BI. It analyzes supermarket transactional data to extract insights into sales, customer behavior, payment modes, and product performance across cities and branches.

## Dataset Source

Kaggle Dataset:  
[Supermarket Sales – Kaggle](https://www.kaggle.com/datasets/faresashraf1001/supermarket-sales)

## Project Objectives

- Preprocess and analyze data using Python
- Visualize KPIs and trends using Power BI
- Understand customer preferences and branch-wise performance
- Provide interactive filtering for data-driven decisions

## Python Analysis

The `SalesAnalysisProject.ipynb` file contains:

- Loading and cleaning the dataset
- Exploratory Data Analysis (EDA)
- Feature engineering (e.g., calculating predicted sales)
- Exporting processed data for use in Power BI

## Power BI Dashboard Overview

### Visuals Included:
- KPI Cards: Total Sales, Quantity, Gross Income, Average Rating
- Bar Chart: Sales by City
- Donut Chart: Payment Method Breakdown
- Stacked Bar: Gender vs Gross Income
- Line Chart: Sales Trend Over Time
- Slicers: City, Branch, Product Line, Month, Gender, Customer Type


## Project Structure

Supermarket-Sales-Analysis/
│
├── SalesAnalysisProject.ipynb              # Python notebook for preprocessing & EDA
├── supermarket_sales - Sheet1.csv          # Original dataset
├── supermarket_sales_with_predictionss.xlsx # Cleaned/enhanced dataset used in Power BI
├── SalesDashboard_Project.pbix             # Power BI dashboard file
├── DashboardPreview.png                    # Power BI dashboard preview image
├── requirements.txt                        # Python dependencies
├── README.md                               # This documentation


## Installation & Setup (for Python)

### 1. Clone the repository:

git clone https://github.com/<your-username>/Supermarket-Sales-Analysis.git
cd Supermarket-Sales-Analysis


### 2. Install required libraries:

```
pip install -r requirements.txt
```

### 3. Run the notebook:

Open `SalesAnalysisProject.ipynb` in Jupyter Notebook or VS Code.

## requirements.txt
Dependencies for Python analysis:

```
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

## Tools Used

- Python (pandas, matplotlib, seaborn, scikit-learn)
- Power BI Desktop
- Jupyter Notebook
- Excel/CSV for data formatting

