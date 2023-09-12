# Pakistan_Ecommerce

Understanding dataset: 
1. Using panda's read_csv function to load the dataset into the jupyter notebook. 
2. The column name for the dataset inlues: 
    ['item_id', 'status', 'created_at', 'sku', 'price', 'qty_ordered',
       'grand_total', 'increment_id', 'category_name_1',
       'sales_commission_code', 'discount_amount', 'payment_method',
       'Working Date', 'BI Status', ' MV ', 'Year', 'Month', 'Customer Since',
       'M-Y', 'FY', 'Customer ID', 'Unnamed: 21', 'Unnamed: 22', 'Unnamed: 23',
       'Unnamed: 24', 'Unnamed: 25']

3. Based on the info() function, the dataset has 26 columns (variables) and 1048575 observations. 

4. Since there are 5 unnamed columns with only "NaN", these columns can be removed. 

5. Based on the Non_Null Count in the dataset, most variables has 584524 observations.