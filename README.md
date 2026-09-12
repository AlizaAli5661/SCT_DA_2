# SCT_DA_2 – Data Cleaning and Preparation

## Task Objective

Perform data cleaning and preparation on a cafe sales dataset to make the data suitable for analysis.

## Dataset

The dataset contains cafe sales transaction records with the following columns:

- Transaction ID
- Item
- Quantity
- Price Per Unit
- Total Spent
- Payment Method
- Location
- Transaction Date

## Data Cleaning Steps

The following steps were performed using Python and Pandas:

1. Loaded the raw cafe sales dataset.
2. Checked the dataset shape, columns, data types, missing values, and duplicates.
3. Replaced invalid `ERROR` and `UNKNOWN` values with missing values.
4. Handled missing categorical values.
5. Converted Quantity, Price Per Unit, and Total Spent into numerical data types.
6. Filled missing Quantity and Price Per Unit values using their median values.
7. Recalculated Total Spent using Quantity × Price Per Unit.
8. Converted Transaction Date into datetime format.
9. Filled missing Transaction Date values.
10. Performed a final validation of the cleaned dataset.
11. Saved the cleaned dataset as `cafe_sales_cleaned.csv`.

## Final Dataset

After cleaning:

- Rows: 10,000
- Columns: 8
- Missing values: 0
- Duplicate records: 0

## Tools Used

- Python
- Pandas
- Jupyter Notebook
- VS Code
- GitHub

## Files

- `cafe_sales_raw_dataset.csv` – Original raw dataset
- `cafe_sales_cleaned.csv` – Cleaned dataset
- `datacleaning.ipynb` – Data cleaning notebook

## Author

**Aliza Ali**
ss