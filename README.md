# Mall Customer Data Analysis Project

This project performs data cleaning and preprocessing on a mall customer dataset to prepare it for further analysis.

## Dataset Description

The dataset (`Mall_Customers.csv`) contains the following features:
- CustomerID: Unique identifier for each customer
- Gender: Customer's gender (Male/Female)
- Age: Customer's age in years
- Annual Income (k$): Customer's annual income in thousands of dollars
- Spending Score (1-100): Customer's spending score based on behavior and purchasing data

## Setup Instructions

1. Clone this repository
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook EL_Task1_DA.ipynb
   ```

## Project Structure

- `EL_Task1_DA.ipynb`: Main Jupyter notebook containing the data cleaning and preprocessing steps
- `Mall_Customers.csv`: Original dataset file
- `Mall_Customers_Cleaned.csv`: Cleaned and preprocessed dataset
- `requirements.txt`: List of Python dependencies
- `README.md`: Project documentation

## Data Cleaning Steps

1. Column Standardization:
   - Renamed columns to lowercase with underscores
   - Standardized text fields (e.g., gender values)

2. Data Quality Checks:
   - Checked for missing values
   - Removed duplicate rows
   - Verified data types

3. Data Type Conversion:
   - Ensured age values are integers
   - Standardized text fields

4. Output:
   - Generated cleaned dataset as 'Mall_Customers_Cleaned.csv'

## Dependencies

- pandas: Data manipulation and analysis
- numpy: Numerical computing
- jupyter: Interactive notebook environment 