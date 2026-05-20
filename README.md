# Amazon Product Sales Analysis 📊

## Overview

This project focuses on analyzing Amazon product sales data using Python for data cleaning, preprocessing, exploratory data analysis (EDA), and business insight generation.

The notebook explores product ratings, pricing, reviews, category performance, and relationships between multiple variables to identify useful business insights from e-commerce sales data.

---

## Objectives

* Understand the structure of Amazon sales data
* Clean and preprocess raw data
* Handle missing values and duplicates
* Perform exploratory data analysis (EDA)
* Visualize trends and relationships
* Generate actionable business insights

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Project Structure

```bash
Sales_Analysis.ipynb
README.md
amazon_products_sales_data_cleaned.csv
```

---

## Dataset Features

The dataset includes product-related information such as:

* Product Name
* Product Category
* Product Price
* Product Ratings
* Total Reviews
* Sales Information
* Discounts
* Product Popularity Metrics

---

## Workflow

### 1. Data Loading

The dataset is imported using Pandas.

```python
import pandas as pd

df = pd.read_csv("amazon_products_sales_data_cleaned.csv")
```

---

### 2. Dataset Overview

Basic dataset inspection is performed:

* Shape of dataset
* Data types
* Statistical summary
* Null value inspection

---

### 3. Data Cleaning

The notebook performs:

* Missing value handling
* Duplicate removal
* Data type conversion
* Numerical data preprocessing

---

### 4. Exploratory Data Analysis (EDA)

Several visualizations and analyses are performed including:

* Distribution of product ratings
* Top product categories by sales
* Price vs rating analysis
* Correlation heatmap
* Review analysis

---

## Visualizations Included

The notebook contains multiple visualizations using Matplotlib and Seaborn:

* Histograms
* Bar charts
* Scatter plots
* Heatmaps
* Count plots

These visualizations help identify patterns and trends within the sales data.

---

## Key Insights

Some important business insights generated from the analysis include:

* High-rated products tend to receive more reviews
* Certain product categories dominate sales performance
* Product pricing impacts customer ratings and engagement
* Review count can influence product popularity

---

## How to Run the Project

### Step 1: Clone the Repository

```bash
git clone <your-repository-url>
cd <repository-folder>
```

### Step 2: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 3: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 4: Open the Notebook

Open:

```bash
Sales_Analysis.ipynb
```

Run all cells to reproduce the analysis.

---

## Future Improvements

Possible future enhancements:

* Build machine learning models for sales prediction
* Create interactive dashboards using Power BI or Streamlit
* Add recommendation system features
* Deploy the project as a web application
* Perform advanced customer sentiment analysis

---

## Learning Outcomes

This project helps in understanding:

* Real-world data preprocessing
* Exploratory data analysis techniques
* Data visualization best practices
* Business intelligence using Python
* Practical use of Pandas and Seaborn

---

## Author

Nischit Kanthala

---

## License

This project is open-source and available for learning and
