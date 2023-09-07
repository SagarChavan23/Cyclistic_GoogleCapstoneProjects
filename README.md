# Cyclistice_GoogleCapstoneProject
**Project Overview**

**Project Objective:** To analyze Cyclistic's bike rental data and gain insights into user behavior, differentiating between annual members and casual riders, and to provide recommendations for optimizing membership and ridership.

**Dataset**: Cyclistic trip data from August 2020 to July 2021.

**Project Steps**
Data Collection: The project began with the collection of historical trip data from Cyclistic's bike-sharing program. The dataset was stored in Google Cloud Storage (GCS) for further processing.
Data Compilation and Cleaning (SQL): The data was imported into BigQuery for manipulation and analysis using SQL. The data was cleaned, and missing values were handled. Duplicate rows and records with negative or zero ride duration values were removed. Additionally, consistent data types were enforced.

Data Visualization (Tableau): The cleaned data was imported into Tableau for visualization and analysis. A variety of visualizations were created to understand user behavior, including user type distribution, total rides by bike type, ride length by weekday, total rides by weekday, total rides by hour, and total rides by month.
Dashboard Design (Tableau): To effectively communicate the insights, a well-designed Tableau dashboard was created. The dashboard included interactive visualizations, annotations, and design elements to enhance clarity and aesthetics.
Report Creation: This report summarizes the entire analysis process, including the code used for data cleaning and preparation, detailed data visualizations, in-depth insights, and recommendations.

**Data Cleaning and Preparation**

Data Compilation and Cleaning (SQL Code)
The following SQL code snippet provides details of the data compilation and cleaning process:

sql code:
The data cleaning process includes rounding ride length values, creating a readable "month" column, removing rows with NA values, duplicates, negative or zero ride length values, and unnecessary columns.

**Data Visualizations**
User Type Distribution

Insights:

Annual members make up the majority of users, representing 58.6% of total rides.
Casual riders account for 41.4% of total rides.
Total Rides by Bike Type
Total Rides by Bike Type

Insights:

The majority of rides are taken on standard bikes, followed by electric bikes and dockless bikes.
Ride Length by Weekday
Ride Length by Weekday

Insights:

Casual riders have longer average ride durations compared to annual members.
Both user types experience longer rides on weekends.
Total Rides by Weekday
Total Rides by Weekday

Insights:

Casual riders tend to use the service more on weekends than weekdays.
Weekday usage by casual riders is approximately 50% lower compared to weekends.
Total Rides by Hour
Total Rides by Hour

Insights:

Casual riders' proportion increases during non-commuting hours, indicating leisurely use.
Annual members dominate peak commuting hours.
Total Rides by Month (Seasonality)
Total Rides by Month

Insights:

Casual riders' proportion drops during winter months but peaks in the summer.
Winter months see a decrease in casual ridership, while summer months show increased usage.
The Tableau dashboard design is detailed below, highlighting the key elements and visualizations:

**Tableau Dashboard**

Dashboard Highlights:

User Type Distribution
Total Rides by Bike Type
Ride Length by Weekday
Total Rides by Weekday
Total Rides by Hour
Total Rides by Month
**Conclusion**

The analysis of Cyclistic's bike rental data reveals valuable insights into user behavior. Key findings include:

Annual members are the majority of users, making up 58.6% of total rides.
Casual riders tend to use the service for leisure, with longer rides on weekends.
Annual members use the service primarily for commuting during peak hours.

**Recommendations**

Based on the insights, several recommendations can be made to optimize Cyclistic's operations:

Targeted Marketing: Implement marketing strategies in leisure-oriented places to attract more casual riders.
Weekday Discounts: Launch discounting campaigns for casual riders on weekdays to encourage commuting usage.
Push Notifications: Utilize push notifications to attract casual riders during off-peak hours.
Seasonal Campaigns: Develop special campaigns, possibly tied to holidays or Christmas, to boost ridership during winter months.

**Project Improvements**

For future iterations of this project, consider the following improvements:

Real-time Data: Analyze real-time data to make more timely decisions and adapt marketing strategies dynamically.
Predictive Modeling: Implement predictive modeling to forecast rider behavior and demand patterns.
A/B Testing: Conduct A/B testing on marketing strategies to determine their effectiveness.
Customer Surveys: Collect user feedback through surveys to better understand preferences and pain points.
Final Thoughts

The analysis of Cyclistic's bike rental data provides valuable insights for improving user experiences and increasing annual memberships. By implementing the recommended strategies and continuously refining the analysis process, Cyclistic can further enhance its services and remain a leading bike-sharing program in Chicago.

