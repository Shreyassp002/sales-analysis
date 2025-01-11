# Sales Data Analysis


## Project Overview
This project involves analyzing a dataset containing Diwali sales information. The goal is to gain insights into customer purchasing behavior during the festive season. We have explored various factors such as gender, age group, marital status, occupation, state, and product categories to determine key trends and patterns.

## Dataset
The dataset used for this project is `Diwali_Sales_Data.csv`, which contains information about orders, amounts, customer demographics, and product categories.

### Features:
- **Gender**: Gender of the customer
- **Age Group**: Age group of the customer
- **Marital Status**: Marital status of the customer
- **State**: State from where the order was placed
- **Occupation**: Occupation of the customer
- **Product Category**: Category of the product purchased
- **Product ID**: Unique identifier for products
- **Orders**: Number of orders placed
- **Amount**: Total amount spent


## Data Cleaning
1. Dropped unrelated or blank columns: `Status`, `unnamed1`.
2. Checked for null values and dropped rows with missing data.
3. Changed the data type of the `Amount` column to integer.
4. Renamed the `Marital_Status` column to `Shaadi` for better readability.


## Exploratory Data Analysis (EDA)
### 1. Gender Analysis
- A bar chart was plotted to show the count of buyers by gender.
- A bar chart was plotted for total sales amount by gender.
- **Insight**: Most buyers are females, and they also have higher purchasing power than males.

### 2. Age Group Analysis
- A bar chart was plotted for the count of buyers by age group and gender.
- A bar chart was plotted for total sales amount by age group.
- **Insight**: Most buyers are in the 26-35 age group, with females dominating the purchasing pattern.

### 3. State Analysis
- A bar chart was plotted for the total number of orders from the top 10 states.
- A bar chart was plotted for total sales amount from the top 10 states.
- **Insight**: Most orders and total sales come from Uttar Pradesh, Maharashtra, and Karnataka.

### 4. Marital Status Analysis
- A bar chart was plotted to show the count of buyers by marital status.
- A bar chart was plotted for total sales amount by marital status and gender.
- **Insight**: Married women have higher purchasing power.

### 5. Occupation Analysis
- A bar chart was plotted to show the count of buyers by occupation.
- A bar chart was plotted for total sales amount by occupation.
- **Insight**: Most buyers work in IT, Healthcare, and Aviation sectors.

### 6. Product Category Analysis
- A bar chart was plotted to show the count of sold products by category.
- A bar chart was plotted for total sales amount by product category.
- **Insight**: The most sold products are from Food, Clothing, and Electronics categories.

### 7. Top 10 Most Sold Products
- A bar chart was plotted to show the top 10 most sold products by orders.


## Conclusion
- **Key Insights**:
  - Married women aged 26-35 years from Uttarpradesh, Maharashtra, and Karnataka working in IT, Healthcare, and Aviation sectors are more likely to buy products.
  - The most popular product categories are Food, Clothing, and Electronics.


## Tools and Libraries Used
- **Python**: For data analysis and visualization.
- **Libraries**:
  - `pandas`: For data manipulation and analysis.
  - `numpy`: For numerical operations.
  - `matplotlib`: For data visualization.
  - `seaborn`: For advanced data visualization.



## How to Run the Project
1. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
2. Run the Python script or Jupyter Notebook.
3. Ensure that the `Diwali Sales Data.csv` file is in the same directory as the script.

---
