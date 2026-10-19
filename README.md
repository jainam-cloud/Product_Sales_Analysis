# Diwali Sales Analysis

## Project Overview
This project explores Diwali sales data using Python to understand customer purchasing patterns and identify trends across customer demographics, locations, occupations, and product categories.

The analysis is performed in a Jupyter Notebook using Pandas, NumPy, Matplotlib, and Seaborn.

## Objectives
- Clean and prepare the sales dataset for analysis.
- Explore customer demographics, including gender, age group, and marital status.
- Compare orders and sales across states.
- Analyze customer occupations and product categories.
- Visualize patterns that can help summarize customer purchasing behavior.

## Tools and Libraries
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Dataset
The notebook uses a dataset named `Diwali Sales Data.csv`.

Place the CSV file in the project folder before running the notebook, and update the file path in the data-loading cell if needed. The dataset contains customer and purchase information such as gender, age, state, occupation, product category, number of orders, and purchase amount.

## Project Files
- `Product_Sales_Analysis.ipynb` — notebook containing data cleaning, exploratory analysis, charts, and conclusions.
- `Diwali Sales Data.csv` — input dataset (include it in this repository only if you have permission to share it).

## Data Cleaning and Preparation
The notebook:
- Inspects the dataset structure and summary information.
- Removes the empty `Status` and `unnamed1` columns.
- Checks for missing values.
- Removes rows with missing values in the dataset; the notebook identifies 12 missing values in `Amount`.
- Uses the cleaned data for exploratory analysis.

After cleaning, the notebook contains 11,239 rows and 13 columns.

## Analysis Performed
The exploratory data analysis includes:
- **Gender:** customer counts and total purchase amount by gender.
- **Age group:** customer counts by age group and gender, and purchase amount by age group.
- **State:** top 10 states by number of orders and total purchase amount.
- **Marital status:** customer counts and purchase amount by marital status and gender.
- **Occupation:** customer counts and purchase amount by occupation.
- **Product category:** product counts and total purchase amount by category.

## Key Findings
Based on the notebook's visualizations and written observations:
- Female customers account for more buyers and a higher total purchase amount than male customers.
- The 26–35 age group is the largest buyer group in the analysis.
- Uttar Pradesh, Maharashtra, and Karnataka are highlighted among the leading states for orders and sales.
- The notebook identifies IT, Healthcare, and Aviation among the occupations associated with many buyers.
- Food, Clothing, and Electronics are highlighted among the leading product categories by sales.

These findings reflect the exploratory analysis in this notebook and should be interpreted in the context of the dataset.

## How to Run the Project
1. Download or clone this repository.
2. Make sure `Product_Sales_Analysis.ipynb` and `Diwali Sales Data.csv` are in the project folder.
3. Install the required libraries if they are not already installed:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `Product_Sales_Analysis.ipynb`.
6. Update the CSV path in the notebook to a relative path, for example:

   ```python
   df = pd.read_csv("Diwali Sales Data.csv", encoding="unicode_escape")
   ```

7. Run the notebook cells from top to bottom.

## Future Improvements
- Add more detailed comparisons and summary metrics.
- Improve chart labels and formatting for easier interpretation.
- Add a concise business-insights section supported by calculated values.
- Make the notebook reproducible using relative file paths.

## Author
Jainam Bhatt
jainam-cloud
