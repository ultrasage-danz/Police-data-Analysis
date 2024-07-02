# Police Dataset Analysis

This Jupyter Notebook contains an analysis of a police dataset using Pandas DataFrames.

## Steps:

1. **Data Loading:** The dataset is loaded from a CSV file using `pd.read_csv()`.

2. **Data Cleaning:** The column 'country_name' is removed as it contains only missing values.

3. **Speeding Analysis:** The number of men and women stopped for speeding is compared using `value_counts()`.

4. **Search Analysis:** The relationship between gender and search conducted during a stop is analyzed using `groupby()` and `sum()`.

5. **Stop Duration Analysis:** The mean stop duration is calculated after mapping the duration categories to numerical values.

6. **Age Distribution Analysis:** The age distributions for each violation are compared using `groupby()` and `describe()`.

## Libraries Used:

- Pandas
- NumPy

## Instructions:

- Make sure to have the Police Data.csv file in the specified path.
- Run the notebook cells sequentially to perform the analysis.
