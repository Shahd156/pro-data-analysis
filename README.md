# Supermarket Sales Analysis

## Project overview

This project analyzes supermarket transactions to explore sales performance, customer purchasing behavior, branch differences, payment methods, and time-based purchasing patterns. It combines data wrangling, exploratory data analysis, visualization, and business recommendations.

## Objectives

- Identify patterns in sales performance across branches.
- Explore the relationship between quantity, sales totals, tax, and customer ratings.
- Examine purchasing behavior by date, time, payment method, and customer type.
- Translate the analysis into practical recommendations for inventory, promotions, staffing, and customer experience.

## Dataset

The analysis uses a supermarket sales dataset containing transaction-level records. The main fields discussed in the analysis include:

- Branch and city.
- Customer type and gender.
- Product line.
- Quantity, unit price, tax, and total transaction value.
- Date, time, payment method, and customer rating.

The raw dataset is not stored in this repository. The notebook and reports document the analysis performed on the source data.

## Methodology

1. Inspect the dataset structure, data types, missing values, and duplicates.
2. Standardize date and time fields and create useful time-based features.
3. Review numerical distributions and relationships between key measures.
4. Compare sales behavior across branches and product-related dimensions.
5. Use visualizations to communicate trends and relationships.
6. Summarize the findings as business recommendations.

## Key analysis areas

### Data wrangling

- Missing-value checks.
- Duplicate checks.
- Date and time conversion.
- Feature engineering for month, day, and time-based analysis.
- Validation of numerical fields.

### Exploratory analysis

- Correlation heatmap for key numerical variables.
- Branch performance comparisons.
- Monthly and daily sales patterns.
- Payment and customer behavior analysis.
- Time-of-day purchasing patterns.

### Business recommendations

- Adjust inventory planning according to demand patterns.
- Use targeted promotions during slower periods.
- Develop branch-specific marketing campaigns.
- Use high-activity periods to plan staffing and stock availability.
- Continue monitoring customer experience alongside sales performance.

## Repository contents

- `project data analysis2.ipynb` — analysis notebook.
- `Data Wrangling Report.pdf` — data preparation report.
- `Business Insights Report.pdf` — findings and recommendations report.
- `README.md` — project documentation.

## Tools and technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- GitHub

## How to review the project

1. Open `project data analysis2.ipynb` to follow the analysis workflow.
2. Read `Data Wrangling Report.pdf` for the preparation steps.
3. Read `Business Insights Report.pdf` for the findings and recommendations.
4. If you want to rerun the notebook, place the permitted source dataset in the expected local path and update the loading cell as needed.

## Portfolio note

This project demonstrates practical skills in data cleaning, exploratory data analysis, feature engineering, visualization, correlation analysis, and communicating business insights from transactional data.
