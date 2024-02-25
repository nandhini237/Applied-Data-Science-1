Detailed Report: Insights from Retail Sales Data Analysis

Author: Nandhini Reddy Kothakapu
Student Number: 23027501
GitHub Repository: https://github.com/nandhini237/Applied-Data-Science-1
________________________________________
Introduction
This detailed report delves into the analysis of a retail sales dataset, highlighting customer demographics, purchasing patterns, and product performance through statistical analysis and data visualization. The dataset consists of 1000 transactions, featuring columns such as Transaction ID, Date, Customer ID, Gender, Age, Product Category, Quantity, Price per Unit, and Total Amount. This exploration aims to uncover actionable insights to guide business decisions.
Data Preparation and Overview
The dataset was loaded into a panda DataFrame, a powerful tool for data manipulation and analysis in Python. Initial exploration involved reviewing the first few rows to understand the data's structure and identify which columns contained numerical or categorical data. This step is crucial for planning subsequent analyses and visualizations.
The structure of data suggests various analyses and visualizations can be performed, such as customer demographics, sales trends over time, and product category performance.
The basic statistics and correlations provide the following insights:

Basic Statistics
•	The dataset contains 1000 transactions.
•	Age: Customers range from 18 to 64 years old, with an average age of approximately 41 years.
•	Quantity: The quantity of products purchased in each transaction ranges from 1 to 4, with an average of about 2.5.
•	Price per Unit: Prices per unit range from $25 to $500, with a mean of approximately $179.89.
•	Total Amount: The total amount spent per transaction ranges from $25 to $2000, with a mean of $456.

Correlations
•	There's a significant positive correlation (≈0.85) between Price per Unit and Total Amount, indicating that as the price per unit increases, the total amount spent also increases, which is expected.
•	Quantity and Total Amount have a moderate positive correlation (≈0.37), suggesting that transactions involving higher quantities of products tend to have higher total amounts, although not as strongly correlated as price per unit to total amount.
•	Other correlations between the fields like Age and Total Amount or Quantity and Price per Unit are relatively weak, suggesting less direct relationships.

Statistical Analysis
Using pandas, we generated descriptive statistics for numerical columns (Age, Quantity, Price per Unit, Total Amount) to obtain a broad overview of the data. This included measures of central tendency (mean, median) and dispersion (min, max, standard deviation), providing insight into the distribution and range of values. For instance, the average age of 41 years suggests a mature customer base, while the wide range in Total Amount indicates diversity in purchasing behaviour.

Correlation Analysis
I examined correlations among numerical variables to identify potential relationships. The strong positive correlation between Price per Unit and Total Amount suggests that higher-priced items significantly contribute to sales. This insight is valuable for inventory management and pricing strategies. Correlations were visualized using a heatmap, making it easier to identify significant relationships briefly.

Visualizations
1.	Age Distribution Histogram: A histogram of customer ages, with kernel density estimation (KDE) for a smoother distribution curve, provides insights into the customer demographic. This visualization helps in tailoring marketing strategies to target age groups more effectively.
 
2.	Total Amount vs. Price per Unit Scatter Plot: By plotting these variables against each other and distinguishing points by Gender and Product Category, we can observe how spending varies across different segments. This plot is instrumental in understanding how product pricing impacts sales and how this relationship may differ by gender and product type.
 
3.	Correlation Heatmap: A heatmap of correlation coefficients between numerical variables offers a concise visual summary of their relationships. It highlights the strongest correlations in the dataset, guiding further analysis and strategy development.
 
Conclusion and Implications
The analysis of the retail sales dataset revealed critical insights into customer demographics, purchasing behaviours, and the impact of pricing on sales. The identified patterns and relationships can inform targeted marketing campaigns, product pricing adjustments, and inventory strategies tailored to customer preferences and behaviours.
This report, supported by detailed statistical and visual analysis, underscores the importance of data-driven decision-making in retail. By leveraging such insights, retailers can optimize their offerings and strategies to meet customer needs more effectively, driving sales and enhancing customer satisfaction.
Future analyses could expand on this foundation by incorporating time-series analysis to understand sales trends over time, or cluster analysis to identify distinct customer segments for more personalized marketing efforts.

