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

6. Removing dataset that contains NaN. 

7. Convert DataFrame to TimeSeries and convert "date" into 'year', 'month', and 'date'

8. Splicing using pandas library to extract data based on year ['2016', '2017', '2018'] for visualization.

9. Focused on the 'price' variable and use matplotlib.pyplot to generate both a line graph and a bar graph for the sales in each day in July 2016. After the visualization, the bar graph definitely did a better job at showing the changes within a month for sales. 

10. Work on categorical variable 'category_name_1' and use DataFrame.pivot_table function to count the observations under each catogory. Created a pie char to visualize the proportion of each catogory during the three year span from 2016 to 2018. 