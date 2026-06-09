# 🍽️ Restaurant Sales Analysis – Simplilearn Capstone Project

## Overview

This capstone project was completed as part of the Simplilearn Data Analytics program. The objective is to analyze restaurant sales data, identify sales patterns, evaluate item performance, and generate actionable business insights through data analysis and visualization.

The project integrates data from multiple sources including restaurant information, menu items, and sales transactions to create a comprehensive analytical dataset.

---

## Project Objectives

- Analyze restaurant sales performance.
- Identify top-performing menu items.
- Understand customer purchasing patterns.
- Evaluate pricing and calorie-related trends.
- Generate business insights using data visualization.
- Demonstrate data cleaning, transformation, and exploratory data analysis (EDA) skills.

---

## Dataset Description

The project uses three datasets:

### 1. `items.csv`
Contains menu item information.

| Column | Description |
|----------|-------------|
| id | Item ID |
| store_id | Restaurant ID |
| name | Item Name |
| kcal | Calories |
| cost | Item Cost |

### 2. `restaurants.csv`
Contains restaurant/store information.

| Column | Description |
|----------|-------------|
| id | Store ID |
| name | Store Name |

### 3. `sales.csv`
Contains transaction-level sales data.

| Column | Description |
|----------|-------------|
| date | Transaction Date |
| item_id | Sold Item ID |
| price | Selling Price |
| item_count | Quantity Sold |

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

- Imported datasets from Google Drive.
- Loaded sales, restaurant, and item information into Pandas DataFrames.

### 2. Data Exploration

- Examined dataset dimensions.
- Checked data types.
- Generated summary statistics.
- Identified missing values.

### 3. Data Cleaning

- Removed duplicate columns after merging.
- Renamed columns for better readability.
- Verified dataset consistency.

### 4. Data Integration

Merged:

- Sales data
- Item details
- Restaurant details

to create a unified dataset for analysis.

### 5. Exploratory Data Analysis (EDA)

Performed analysis on:

- Sales trends
- Item popularity
- Revenue distribution
- Restaurant performance
- Price patterns
- Calorie distribution

### 6. Visualization

Used Matplotlib and Seaborn to create visual insights including:

- Sales trends
- Distribution plots
- Comparative analysis charts
- Restaurant performance visualizations

---

## Key Insights

The analysis helps answer questions such as:

- Which menu items generate the highest sales?
- Which restaurants perform best?
- How does pricing affect sales volume?
- What are the most popular food categories?
- Are there seasonal or time-based sales patterns?

---

## Repository Structure

```text
Simplilearn-Capstone/
│
├── Capstone.ipynb          # Main analysis notebook
├── items.csv               # Menu item dataset
├── restaurants.csv         # Restaurant dataset
├── sales.csv               # Sales transactions dataset
└── README.md               # Project documentation
```

---

## How to Run

### Clone Repository

```bash
git clone https://github.com/HarishKL01/Simplilearn-Capstone.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

### Launch Notebook

```bash
jupyter notebook
```

Open:

```text
Capstone.ipynb
```

and run all cells sequentially.

---

## Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Data Merging
- Exploratory Data Analysis
- Data Visualization
- Business Analytics
- Python Programming
- Statistical Analysis

---

## Results

The project successfully combines multiple restaurant datasets into a single analytical framework, enabling detailed exploration of sales performance and supporting data-driven decision making for restaurant operations.

---

## Author

**Rahul Harish**

- GitHub: https://github.com/HarishKL01
- Simplilearn Capstone Project

---

## License

This project is intended for educational and learning purposes.
