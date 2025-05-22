# Electrical-Energy-Consumption-Analysis-Dashboard
Developed a Power BI dashboard for in-depth electrical energy consumption analysis, incorporating comprehensive data cleaning to uncover key usage patterns and trends from a Kaggle dataset.

Project Overview
This project involved creating an interactive Power BI dashboard to analyze electrical energy consumption data. By combining and transforming raw datasets, the goal was to uncover trends, identify key drivers of energy consumption, and provide actionable insights for optimizing energy usage and understanding consumption patterns within different building types.
Dataset
The primary datasets used for this analysis are sourced from Kaggle:
•	Energy Consumption Dataset (Linear Regression): https://www.kaggle.com/datasets/govindaramsriram/energy-consumption-dataset-linear-regression?select=train_energy_data.csv
Specifically, the train_energy_data.csv and test_energy_data.csv files were utilized. These datasets contain key information such as Building Type, Square Footage, Number of Appliances, Average Temperature, Day of Week, and Energy Consumption.


Data Acquisition and Preparation


The project involved combining and extensively cleaning the train_energy_data.csv and test_energy_data.csv files within Power Query to ensure data quality, consistency, and suitability for comprehensive analysis.
Data Cleaning and Transformations Performed:
•	Appending Datasets: The train_energy_data.csv and test_energy_data.csv files were appended into a single, unified dataset for comprehensive analysis.
•	Column Consistency: Essential columns like Building Type, Square Footage, Number of Appliances, Average Temperature, Day of Week, and Energy Consumption were verified for consistency across the combined dataset.
•	Data Type Conversion: Numerical columns (Square Footage, Number of Appliances, Average Temperature, Energy Consumption) were converted to appropriate numeric data types to enable calculations and aggregations. Categorical columns like Building Type and Day of Week were ensured to be correctly identified as text.
•	Addressing Missing Values: Missing values within the dataset were addressed to maintain data integrity and ensure accurate analysis.
•	Feature Engineering: New categorical columns were created based on Average Temperature (e.g., 'Cool', 'Warm', 'Moderate' groups) and Number of Appliances (into bins) to facilitate specific analyses as seen in the dashboard visualizations.


Power BI Dashboard Features


The Power BI dashboard was designed to be interactive and user-friendly, allowing for dynamic exploration of the energy consumption data. Key features include:
•	Interactive Filters: Slicers and filters, such as the "Building Type" filter, allow users to drill down into specific building categories or other dimensions of interest.
•	Dynamic Visualizations: All charts and graphs on the dashboard respond to user selections, providing real-time updates and insights.
•	Clear and Concise Layout: The dashboard is organized logically, guiding users through the data story with a visually appealing and easy-to-understand structure.


Key Visualizations and Outcomes


The following visualizations were developed to illustrate key aspects of energy consumption and provided valuable insights:

1. Total Energy Consumption by Building Type
•	Type of Visualization: Donut Chart
•	Description: This chart shows the distribution of total energy consumption across different building types: Residential, Commercial, and Industrial.
•	Outcomes/Insights: Visually represents the proportion of energy consumed by each sector, allowing for a quick comparison of their overall contribution to total consumption.

2. Total Energy Consumption by Day of Week
•	Type of Visualization: Donut Chart
•	Description: This chart displays the total energy consumption segregated by Day of Week into 'Weekday' and 'Weekend' categories.
•	Outcomes/Insights: Provides an immediate comparison of overall energy usage between the five weekdays and the two weekend days, highlighting any significant differences in total consumption.

3. Sum of Square Footage vs Energy Consumption
•	Type of Visualization: Scatter Plot with Trendline
•	Description: This scatter plot explores the relationship between the Sum of Square Footage of buildings and their corresponding Energy Consumption.
•	Outcomes/Insights: The trendline helps visualize the general correlation, indicating whether larger buildings tend to consume more energy, and identifying any deviations from this trend.

4. Avg Temperature vs Energy Consumption
•	Type of Visualization: Scatter Plot
•	Description: This scatter plot examines the relationship between Average Temperature and Energy Consumption.
•	Outcomes/Insights: Helps in understanding how variations in ambient temperature might influence energy usage, potentially revealing patterns related to heating or cooling demands.

5. Average of Energy Consumption by Building Type and Day of Week
•	Type of Visualization: Stacked Bar Chart
•	Description: This chart provides a detailed breakdown of the Average of Energy Consumption by Building Type (Industrial, Commercial, Residential) and further by Day of Week (Weekday, Weekend).
•	Outcomes/Insights: Allows for granular insights into which specific building types have higher average consumption during weekdays versus weekends, enabling more targeted analysis.

6. Avg Energy Consumption by Appliances Used (bins)
•	Type of Visualization: Bar Chart
•	Description: This bar chart shows the Average Energy Consumption grouped into distinct bins based on the Number of Appliances Used.
•	Outcomes/Insights: Illustrates the general impact of appliance density on energy consumption, showing how average usage changes as the number of appliances increases across predefined ranges.

7. Count of Energy Consumption by Building Type and Day of Week
•	Type of Visualization: Stacked Bar Chart
•	Description: This chart displays the Count of Energy Consumption records (number of data points) categorized by Building Type and Day of Week.
•	Outcomes/Insights: Provides insight into the volume of data available for each specific combination of building type and day of the week, useful for understanding data distribution.

8. Average of Energy Consumption by Average Temperature (groups)
•	Type of Visualization: Bar Chart
•	Description: This chart groups Average Temperature into qualitative categories (e.g., 'Cool', 'Warm', 'Moderate') and shows the Average Energy Consumption for each group.
•	Outcomes/Insights: Offers a simplified, high-level view of how energy consumption fluctuates with general temperature conditions, making it easier to interpret the broad impact of temperature.

9. Sum of Square Footage vs Energy Consumption (Repeated Chart)
•	Type of Visualization: Scatter Plot
•	Description: This chart is another representation of the relationship between Sum of Square Footage and Energy Consumption.
•	Outcomes/Insights: Reinforces the observed correlation between building size and energy consumption, and can serve as a detailed drill-down or comparative view within the dashboard.
Overall Insights Gained
Through this Power BI dashboard, several key insights into electrical energy consumption patterns and drivers were uncovered:
•	Diverse Consumption by Building Type: Energy consumption is distinctly distributed across Residential, Commercial, and Industrial building types, with each showing unique patterns influenced by the day of the week.
•	Influence of Building Size: Square Footage is a clear factor influencing overall energy consumption, indicating that larger spaces generally require more energy.
•	Temperature Impact: Average Temperature plays a role in energy consumption, with specific temperature ranges potentially leading to higher average consumption (e.g., for heating or cooling demands).
•	Appliance Correlation: The number of appliances used directly correlates with energy consumption, highlighting the impact of electrical appliance density on overall energy demand.
•	Weekday vs. Weekend Patterns: While total consumption might be balanced, the average consumption for specific building types and their overall consumption patterns can vary significantly between weekdays and weekends.


Future Enhancements


•	Integration of Additional Data: Integrate data on specific dates (like holidays or special events), building occupancy rates, or detailed equipment lists to further refine the analysis.
•	Advanced Analytics: Implement predictive models within Power BI or integrate with external tools (such as R or Python) for forecasting future energy consumption based on historical trends and influencing factors.
•	Granular Analysis: Explore the possibility of breaking down consumption by more specific zones, floors, or even individual equipment within buildings, if more granular data becomes available.
•	Cost Analysis: Incorporate energy pricing data to calculate and visualize not just energy consumption, but also the associated costs, offering a more complete financial picture.
________________________________________

