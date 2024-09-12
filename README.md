# Advanced-Sales-Metrics-Exploration

### Project Overview

This case study focuses on analyzing sales data from multiple sources to derive actionable insights. The project involves merging multiple CSV files, cleaning the data, and performing various analyses to answer specific business questions. The goal is to understand sales trends, identify key factors influencing sales, and provide recommendations based on the findings.

### Objecive

The primary objectives of this project are:

- To combine data from multiple CSV files into a single, coherent dataframe.
- To clean and preprocess the data for analysis.
- To answer specific questions regarding sales performance, including identifying the best sales months, top-selling cities, optimal times for advertisements, frequently sold 
  product pairs, and best-selling products.

### Data Sources

CSV Files: 12 CSV files containing sales data, each including columns for date, city, product, and sales figures.

### Tools

- Jupyter Notebook: For data analysis and visualization.
- Pandas: For data manipulation and cleaning.
- Matplotlib: For data visualization.

 
 ### Results and Impact

 #### Merging CSV Files

- Task: Merged 12 CSV files into a single dataframe.
- Method: Used pd.concat() to concatenate files after listing all files in the directory.
- Outcome: Created a unified dataframe with consolidated sales data for further analysis.

 #### Data Cleaning

- Drop NaN Values: Removed rows with missing values to ensure data accuracy.
- Remove Rows Based on Condition: Filtered out irrelevant or erroneous rows based on specific conditions.
- Add Month Column: Extracted and added a month column from date strings for time-based analysis.
- Add Sales Column: Converted sales data to numeric format for accurate calculations.

 #### Sales Analysis

- Best Month for Sales: Determined by aggregating sales data by month and visualizing results with a bar chart.
  ![Graph](/Capture.PNG)
  
- Top-Selling City: Identified by grouping data by city and summing sales figures. A city column was added, and results were visualized using a bar chart.
  ![Graph](/Capture1.PNG)
  
- Optimal Advertisement Time: Analyzed purchase data by hour and minute to determine the best time for advertisements. A line graph was used to visualize peak purchasing 
  times.
  ![Graph](/Capture2.PNG)

 #### Product Analysis

- Frequently Sold Products Together: Identified pairs of products frequently sold together by finding duplicate values and counting pairs using itertools and collections.
   ![Graph](/Capture3.PNG)
  
- Best-Selling Product: Analyzed sales data to identify the top-selling product and provided insights into why it was successful.
  ![Graph](/Capture4.PNG)
 
 ### Recommendations

- Target Advertising: Schedule advertisements during peak purchasing hours identified in the analysis to maximize sales.
- Focus on Top-Selling Cities: Allocate resources and marketing efforts to cities with the highest sales figures.
- Leverage Product Pairing Insights: Promote products that are frequently sold together to boost sales of complementary items.
- Optimize Inventory: Adjust inventory levels based on the best-selling products to meet demand effectively.

  ### Conclusion

The analysis provided valuable insights into sales performance, highlighting key factors that influence sales. By merging and cleaning the data, answering specific business questions, and visualizing the results, the project offered actionable recommendations to enhance sales strategies.

### Future Enhancements

- Expand Data Sources: Incorporate additional data sources, such as customer demographics and online behavior, for a more comprehensive analysis.
- Advanced Analytics: Utilize machine learning techniques to predict future sales trends and customer preferences.
- Automate Reporting: Develop automated reporting tools to streamline the process of generating sales insights and recommendations.
- Enhance Visualizations: Explore advanced visualization techniques and interactive dashboards to better communicate findings.
