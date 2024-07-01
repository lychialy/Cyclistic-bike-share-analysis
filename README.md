# Cyclistic-bike-share-analysis and Marketing Strategy

This is my project on the Cyclistic bike-share case study. This project analyzes the usage patterns of Cyclistic, the fictional bike-share service, focusing on data insights from the company. You'll also find that I've attached CSV files sourced from Google BigQuery that have been cleaned and analyzed for this study.

It compares the behaviors of annual members and casual riders and provides insights into how Cyclistic can convert casual riders to annual members.

## Data
 The data used in this analysis is sourced from the Cyclistic bike-share service, cleaned, and analyzed using SQL in Google BigQuery. The dataset used includes trip data such as start and end times, start and end station names, user types(casual vs. member), and longitude and latitude data fro the stations. 
### Project Scope

-   **Data Analysis**: Using BigQuery, I analyzed Cyclistic's bike usage data to uncover patterns and trends between annual members and casual riders.
-   **Visualization**: I used Tableau to create interactive dashboards that visually represent key insights and findings.
  
Business Task: Analyze historical bike data to understand how annual members and casual riders use Cyclistic bike differently with the intention of designing marketing strategies to convert casual riders into annual members.


There were three questions that I had to focus on:
1. How do annual members and casual riders use Cyclistic bikes differently?
   Casual riders seemed to use bikes for recreational purposes or occasional commutes, while members might use them for more regular commuting and daily activites.
   
3. Why would casual riders buy Cyclistic annual memberships?
   Casual riders may find annual memberships more appealing due to cost savings over time, if they use the bikes frequently. The appeal of unlimited rides, access to bikes at anytime, and not needing to worry about bike maintenace. 
   
5. How can Cyclistic use digital media to influence casual riders to become members?
   Cyclistic could leverage digital media by promoting the finacial benefits and the convenience of annual memberships. They could run ads for positive impacts of bike riding, they can emphasize how beneficial it is for the the environment and body(these advantages could entice more users)
   
## Weekly Usage Analysis
It was also important to measure the weekly usage of bikes. 
| Day of week | Ride count|
|-------------|-------------|
| Monday      | 248621      |
| Tuesday     | 240875      |
| Wednesday   | 269896      |
| Thursday    | 269225      |
| Friday      | 279049      |
| Saturday    | 269062      |
| Sunday      | 295060      |

This table shows the total bike usage for each day of the week. 
For more details, see the [weekly usage data](https://github.com/lychialy/Cyclistic-bike-share-analysis/blob/main/Days_week_usage%20-%20day_of_week_analysis.csv).

### Monthly Analysis

Visualized seasonal trends to show peak usage during spring to late summer, this suggests higher demand during warmer months. 
![Monthly Analysis](https://github.com/lychialy/Cyclistic-bike-share-analysis/blob/main/2024-07-01%20(2).png?raw=true)


### Average Duration and Distance

Casual users have longer average ride duration compared to members. Indicating they may be using bikes for leisure or exploration. Both user types share an average of a little over 1 mile in distance per ride, suggesting similar travel distances. 
![Avg Duration and Distance](https://github.com/lychialy/Cyclistic-bike-share-analysis/blob/main/2024-07-01.png?raw=true)


### Rideable Bike Type Analysis

Found classic bikes as the most used among customers, followed by electric bikes, and then docked bikes. Knowing this helps with managing inventory and maintenance. Understanding which bike types are most utilized provides valuable insights into customer preferences and marketing strategies.

![Bike Types](https://github.com/lychialy/Cyclistic-bike-share-analysis/blob/main/2024-07-01%20(1).png?raw=true)

Link to [Tableau Dashboard with all visuals](https://public.tableau.com/views/CyclisticCaseStudyCapstone_17196371711750/Dashboard1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

## Next Steps

Based on these insights, Cyclistic should continue to analyze user behaviour and preferences to improve its bike-share services before any vital changes or major commitments. It's crucial to gather additional data to make informed decisions, that will ensure that any future strategies are well-founded and aligned to customer needs. 



