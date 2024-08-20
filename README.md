# Diwali Sales Data Analysis

## Project Overview

The Diwali Sales Data Analysis project aims to provide insights into customer purchasing patterns during the Diwali festival. By analyzing a dataset of sales transactions, the project explores various factors such as customer demographics, product categories, and regional sales performance.

## Dataset

The dataset, `Diwali Sales Data.csv`, includes the following columns:
- `User_ID`: Unique identifier for the customer
- `Cust_name`: Name of the customer
- `Product_ID`: Unique identifier for the product
- `Gender`: Gender of the customer
- `Age Group`: Age group category of the customer
- `Age`: Age of the customer
- `Shaadi`: Marital status (0 for unmarried, 1 for married)
- `State`: State where the customer resides
- `Zone`: Geographic zone of the customer
- `Occupation`: Occupation of the customer
- `Product_Category`: Category of the product purchased
- `Orders`: Number of orders placed
- `Amount`: Total amount spent

## Data Preprocessing

1. **Load Data**: Import the dataset and inspect its shape and contents.
2. **Drop Unrelated Columns**: Remove columns with no meaningful data.
3. **Handle Missing Values**: Drop rows with missing values in the `Amount` column.
4. **Change Data Type**: Convert the `Amount` column to integer type.
5. **Rename Columns**: Rename the `Marital_Status` column to `Shaadi`.

## Exploratory Data Analysis (EDA)

1. **Gender Analysis**:
   - Count plot and bar plot of sales amount by gender.
   - Insights: Females are the majority in both count and total sales amount.

2. **Age Analysis**:
   - Count plot and bar plot of sales amount by age group.
   - Insights: Most buyers are in the 26-35 age group, contributing significantly to total sales.

3. **State Analysis**:
   - Bar plots showing total orders and sales amount by state.
   - Insights: Uttar Pradesh, Maharashtra, and Karnataka lead in orders and sales amount.

4. **Marital Status Analysis**:
   - Count plot and bar plot of sales amount by marital status and gender.
   - Insights: Married individuals, especially women, have higher spending power.

5. **Occupation Analysis**:
   - Count plot and bar plot of orders and sales amount by occupation.
   - Insights: IT, Healthcare, and Aviation sectors have the most buyers and highest sales.

6. **Product Category Analysis**:
   - Count plot and bar plot of orders and sales amount by product category.
   - Insights: Food, Clothing, and Electronics are the most popular categories.

7. **Top Products**:
   - Bar plot of the most sold products by order count.

## Conclusion

The analysis reveals that married women aged 26-35 years from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation sectors, are most likely to purchase products in the Food, Clothing, and Electronics categories. These insights can guide targeted marketing strategies and inventory management.

## Requirements

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

## How to Run

1. Clone the repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Place the `Diwali Sales Data.csv` file in the project directory.
4. Run the Jupyter Notebook or Python script to perform the analysis.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

