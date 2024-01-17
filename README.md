# Sales-Performance-Analysis-using-Python
Analyzing Sales Performance by Region in a Retail Company: Performing data aggregation to analyze the sales performance by region and identify the top-performing regions.

#Algorithm
1. Import the pandas library as pd.
2. Read a CSV file named "Retail_Sales.csv" into a DataFrame called df using pd.read_csv().
3. Print information about the DataFrame using the info() method.
4. Print the entire DataFrame.
5. Group the DataFrame by the 'Region' column and calculate the sum of 'Sales_Amount' for each region, resetting the index. Store the result in a variable called sales_by_region.
6. Print the sales_by_region DataFrame.
7. Import the matplotlib.pyplot library as plt.
8. Create a pie chart with the sales distribution by region using plt.pie().
    - Set the figure size to 8x8 inches.
    - Use sales_by_region data for labels and values.
    - Show the percentage on the chart using autopct='%1.1f%%'.
    - Set the start angle to 140 degrees.
    - Add a title: 'Sales Distribution by Region'.
    - Ensure equal aspect ratio with plt.axis('equal').
    - Display the pie chart using plt.show().
9. Sort the sales_by_region DataFrame by 'Sales_Amount' in descending order and store the result in top_performing_regions.
10. Print the top-performing regions based on the highest sales amount.
11. Group the DataFrame by both 'Region' and 'Product_category' columns, calculating the sum of 'Sales_Amount' for each group. Reset the index and store the result in sales_by_region_category.
12. Print the sales_by_region_category DataFrame.
13. Create a stacked bar chart using sales_by_region_category data.
    - Set the figure size to 12x6 inches.
    - Label the x-axis as 'Region' and the y-axis as 'Total Sales'.
    - Add a title: 'Sales Comparison by Region and Product Category'.
    - Display the legend in the upper right corner outside the plot with specific coordinates (1.15, 1).
    - Show the plot using plt.show().

