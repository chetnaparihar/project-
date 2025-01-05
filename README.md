# Call Center Dashboard


## Problem Statement

This dashboard provides insights into the operational performance of a call center. It helps management monitor key metrics like call resolution rates, customer satisfaction, and average speed of answer. By analyzing these metrics, the call center can identify areas for improvement and enhance customer experience.

The dashboard highlights that 72.92% of calls are resolved, while 81.08% of calls are answered. However, improvement is needed in resolution rates and satisfaction levels, as they are critical to customer retention.

Additionally, the average speed of answer is 67.52 seconds, which indicates that further optimizations are required to reduce this time and improve service quality.


### Steps followed 

- Step 1: Data Loading
Imported the dataset into Power BI Desktop in a CSV format.

- Step 2: Data Cleaning
In the Power Query Editor, enabled "Column Distribution", "Column Quality", and "Column Profile" to analyze data quality. Ensured column profiling was based on the entire dataset.

- Step 3: Addressed Null Values
Found that the dataset had negligible null values in some columns, which were excluded during metric calculations.

- Step 4: Key Metric Calculation
Created measures for metrics like:

Number of answered calls.
Number of resolved calls.
Average satisfaction rate.
Step 5: Added Visuals

Pie Charts: To represent the percentage of answered and resolved calls.
Bar Chart: Monthly breakdown of answered and resolved calls.
Gauge Chart: Displayed overall satisfaction rate.
Table: Showcased agent-level statistics, such as average speed of answer, satisfaction rates, and resolved calls.
- Step 6: Customization and Design

Added slicers for filtering by Agent, Topic, and Date Range.
Included a title, logo, and call center icons for better visual appeal.
- Step 7: Published to Power BI Service
Published the final report to Power BI Service for easy access and sharing with stakeholders.


### Conclusion

The dashboard provides a clear picture of call center operations, highlighting areas like resolution rates, speed of answer, and customer satisfaction. By focusing on agent performance and reducing delays, the call center can significantly improve its efficiency and customer experience.

