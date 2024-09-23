# athletic_sales_analysis

1. Import the two CSV files `athletic_sales_202.csv` and `athletic_sales_2021.csv`, and read them into DataFrames.
2. Check similar names and data types between two DataFrames.
3. Combine the two DataFrame by the rows using inner join, and reset the index, after combinin check the following:
    * Null values,
    * Column data type,
    * Convert the `invoice_data` column to datetime data type.
    * Confirm that the data type has been changed.

## Determine which Region Sold the Most Products

1. Using `groupby` and `pivot_table` functions findout which region has sold Most products
2. Create a multi-index DataFrame with `region`, `state` and `city`columns.

## Dtermine which Retailer had the Most Sales

1. Using `groupby` and `pivot_table` functions findout which retailer has most sales.
2. Create a multi-index DataFrame with `retailer`, `region`, `state`, and `city` columns.

## Determine which Retailor Sold the Most Women's Athletic Footwear

1. Filter the combined dataframe to create a DataFrame with only women's athletic footwear sales data.
2. Use `groupby` or `pivot_table` to create multi-index dataframe with `retailer`, `region`, `state`, and `city` columns.
3. Rename the aggregated column to reflect the aggregration of data.

## Determine the Day with the Most Women's Athletic Footwear Sales

1. Create a pivot table with the `invoice_date` column as the index and the `total_sales` column as the values parameter.
2. Rename the aggregated column to reflect the aggregation of the data in the column.
3. Use `resample` function to place data to daily bins 

## Determine the Week with Most Women's Athletic Footwear Sales

1. Similar to above use `resample` function to place data to weekly bins.

