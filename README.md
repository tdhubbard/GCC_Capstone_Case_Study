# GCC_Capstone_Case_Study

# Case Study Title:
Cyclistic Bike-Share Analysis: How to Navigate Speedy Success (Capstone Case Study) 

# Case Study Description:
Cyclistic (A fictional company) launched its successful bike-share program in 2016. The program has since grown to include a fleet of 5,824 geotracked bicycles across 692 stations in Chicago. Cyclistic distinguishes itself by offering a variety of bike options, including reclining bikes, hand tricycles, and cargo bikes, catering to a diverse range of riders. While Cyclistic users are more likely
to ride for leisure, about 30% use the bikes to commute to work each day. Cyclistic’s marketing strategy has historically focused on building general awareness and appealing to broad consumer segments, enabled by flexible pricing plans such as single-ride passes, full-day passes, and annual memberships. Casual riders are those who purchase single-ride or full-day passes, while annual members are those who purchase annual memberships.

# Business Task:
Analyze Cyclistic's historical bike trip data to identify trends and differences in how annual members and casusal riders use Cyclistic bikes. This analysis is to inform the development of targeted marketing strategies to convert casual riders into annual members.

# Skills Demonstrated:
1. Data Wrangling/Data Preparation
2. Data Collection
3. Data Cleaning: Standardized column names; Removed or filtered out irrelevant or erroneous data
4. Data Transformation: Combined datasets into a single dataframe; Converted data and time columns to appropriate formats; Calculated ride lengths; Created columns for day of the week, month, and year
5. Data Analysis
6. Descriptive Statistics: Performed various calculations (e.g., average ride length) to understand the data.
7. Data Aggregation: Grouped data by user type, day of the week, month, and year to compare ride patterns.
8. Exploratory Data Analysis (EDA): Explored the data to identify trends and patterns in bike usage.
9. Filtering and Sorting: Filtered data to remove outliers and sorted data to find the top 10 start stations.
10. Data Visualization: Created histograms to visualize ride length distribution; Created bar plots to compare average ride lengths by user type across different days of the week and months; Visualized the top 10 start stations for each user type using bar plots.
    
# Datasets:
Collected and utilized Datasets Divvy_Trips_2019 and Divvy_Trips_2020

# Tools and Libraries:
R and RStudio were utilized to conduct this case study analysis.
The following packages were loaded and libraries used to conduct analysis and visualizations: readr, dplyr, ggplot2, lubridate, and scales

# Analysis and Findings:
The analysis revealed several key differences in how annual members and casual riders use Cyclistic bikes:

* **Ride Length:** Casual riders take significantly longer rides than annual members. The ride length distribution for casual riders is right-skewed, indicating a mix of short and long rides, while annual members' rides are concentrated at shorter durations.
* **Day of Week Patterns:** Casual riders exhibit the longest rides on weekends, suggesting recreational use. Annual members maintain relatively consistent ride lengths throughout the week, indicating commuting to work patterns.
* **Monthly Patterns:** Ride length patterns remain consistent across months for both user types, with casual riders consistently taking longer rides.
* **Ridership Growth:** Annual membership saw a substantial increase from 2019 to 2020, dwarfing the growth in casual ridership.
* **Start Station Locations:** Annual members primarily start their rides from stations in downtown Chicago, likely for commuting. Casual riders start from a wider range of stations, including those near recreational areas and tourist attractions.

# Visualizations:
Reference Case Study PDF for all visualizations.

# Recommendations
Based on the analysis, the following recommendations are made to convert casual riders into annual members:

1.  **Targeted Marketing Campaigns:** Develop marketing campaigns that appeal to the recreational and leisure-oriented usage patterns of casual riders. Highlight the value of annual memberships for weekend trips, exploring the city, and enjoying scenic rides. 
2.  **Incentivize Weekend/Leisure Use:** Offer membership perks or discounts specifically for weekend or off-peak usage, aligning with casual riders' longer, leisure-focused trips.
3.  **Promote Convenience and Value:** Emphasize the convenience and value of annual memberships for regular use, even beyond commuting. This could include highlighting the ease of access, cost savings for frequent riders, and the availability of bikes for various purposes. 
