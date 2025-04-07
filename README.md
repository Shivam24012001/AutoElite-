AutoElite is a prominent car dealership for a leading automotive brand, operating multiple showrooms across India. Following the launch of new showrooms in the East region in December 2022, the management team set ambitious sales targets for their top models: Hatchback, SUV, and Sedan. To ensure a successful launch and growth, they established specific sales goals across various regions, states, and months. The analysis culminates in the creation of a bar chart that visualizes the monthly, state, and region sales differences, providing insights into performance against targets.

ActualTable 

https://raw.githubusercontent.com/Invact-Abhay/DOE/refs/heads/main/AutoElite_Actual.csv

BudgetTable

https://raw.githubusercontent.com/Invact-Abhay/DOE/refs/heads/main/AutoElite_Budget.csv

Task 1

Import Pandas and Matplotlib.pyplot libraries

Task 2

Print a Data Frame named  “Actual” from the given URL.

Print a Data Frame named 'Budget” from the given URL.

Task 3

Print a Data Frame named 'Budget” from the given URL.

Task 4

 Display the column names for both the Actual and Budget DataFrames.

Task 5

Convert all column names in the Actual and Budget DataFrame to lowercase and replace spaces with underscores.

Task 6

Group the Actual Data Frame by month, region, state, and product, then sum the quantity_sold column and create a new Data Frame with the result stored in a column named actual_quantity.

Task 7

Merge the Budget DataFrame with the Grouped_Actual DataFrame using a left join, based on the month, state, region,  and model columns.

Task 8

Calculate the variance between actual quantity_sold and budgeted_quantity for each row in the merged_table DataFrame and store the result in a new column called variance

Task 9

Create a new column month_number in the merged_table DataFrame by mapping the month names to their corresponding numerical values using a dictionary, and then display the first few rows of the updated DataFrame

Task 10

Group the merged_table by month and month_number, sum the variance for each group and then sort the resulting monthly_merged_table by month_number in ascending order.

Task 11

Create a bar chart using the monthly_merged_table DataFrame, where the month column is plotted on the x-axis and the variance column is plotted as the height of the bars, also label the axes and rotate the x-axis labels by 90 degrees.

Task 12

Create a region_wise_variance_table DataFrame that groups the merged_table by 'region' and calculates the sum of the 'variance' for each region, then resets the index

Task 13

Create a bar chart using the region_wise_variance_table DataFrame, where the 'region' column is plotted on the x-axis and the 'variance' column represents the height of the bars, while also labeling the axes appropriately

Task 14

DataFrame called state_wise_variance_table that summarizes the total variance of sales by state from the merged_table DataFrame, using the group by function to aggregate the 'variance' column

Task 15

Create a bar chart to visualize the state-wise variance in sales using the state_wise_variance_table DataFrame, where the “state” names are on the x-axis and the “variance” values are represented as the height of the bars. 


Additionally, label the axes and rotate the x-axis labels by 90 degrees for better readability

