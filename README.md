# Cyclistic Case Study using SQL and Tableau
#### Prepared by: İlkin Yıldırım

## Introduction
Welcome to the Cyclistic bike-share analysis case study! In this project, I collaborated with a fictional company, Cyclistic, and its key team members to explore and answer critical business questions. By following the data analysis process—Ask, Prepare, Process, Analyze, Share, and Act—I systematically addressed these questions and derived meaningful insights.

The case study was structured around the Case Study Roadmap tables, which provided guiding questions and key tasks, ensuring a clear and organized approach throughout the analysis. This introduction marks the beginning of a comprehensive journey to uncover valuable insights for Cyclistic's bike-share program.

## Scenario
You are a junior data analyst working on the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, your team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, your team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve your recommendations, so they must be backed up with compelling data insights and professional data visualizations.

## Ask
### Business Task
The purpose of this analysis is to address the first key question assigned by Moreno: How do annual members and casual riders use Cyclistic bikes differently? This task involves a comprehensive analysis of bike usage patterns between these two groups. The findings will contribute to the development of targeted marketing strategies to convert casual riders into annual members.

To achieve this, I will produce a detailed report with the following deliverables:

A Clear Statement of the Business Task: Analyze and compare the usage patterns of annual members and casual riders to identify key differences.
A Description of All Data Sources Used:Provide detailed information on the data sources utilized for the analysis, ensuring transparency and replicability.

Documentation of Any Cleaning or Manipulation of Data: Document all steps taken to clean and prepare the data for analysis, including any transformations or adjustments made.

A Summary of Your Analysis: Summarize the key findings and insights derived from the analysis, highlighting the main differences in bike usage between annual members and casual riders.

Supporting Visualizations and Key Findings: Present visualizations that illustrate the key findings, making the data more accessible and understandable.

Your Top Three Recommendations Based on Your Analysis: Provide actionable recommendations for Cyclistic's marketing team to encourage casual riders to become annual members based on the analysis results.
## Prepare
### Data Source
The analysis utilized data from Cyclistic's bike-share system, focusing on ride details, user information, and bike information tables from the 12 months of 2023, sourced from [Divvy's trip data](https://divvy-tripdata.s3.amazonaws.com/index.html), to compare usage patterns between annual members and casual riders.
## Process
Using BigQuery, I combined the files into a single table to streamline analysis. I ensured data integrity by checking and correcting data types, identifying and removing duplicate values, and meticulously documenting the entire cleaning process to guarantee the data was clean and ready for analysis.
## Analyze
I aggregated, organized, and formatted the data, performed necessary calculations, and identified trends and relationships to answer the business questions; the SQL code used can be found [here](https://github.com/Ilkinyldrm/Cyclistic_Case_Study/blob/main/cyclistic_case_study_SQL)
## Share
Using Tableau, I crafted impactful data visualizations that illustrate key insights into the distinct usage patterns of annual members and casual riders within Cyclistic's bike-share program, facilitating clear communication of the findings.
![data visualisation](https://github.com/Ilkinyldrm/Cyclistic_Case_Study/blob/main/Tableau%20images/Monthly%20Total%20Rides.png)


![data visualisation](https://github.com/Ilkinyldrm/Cyclistic_Case_Study/blob/main/Tableau%20images/Monthly%20Average%20Ride%20Length.png)


![data visualisation](https://github.com/Ilkinyldrm/Cyclistic_Case_Study/blob/main/Tableau%20images/Weekly%20Total%20Rides.png)


![data visualisation](https://github.com/Ilkinyldrm/Cyclistic_Case_Study/blob/main/Tableau%20images/Weekly%20Ride%20Length.png)


![data visualisation](https://github.com/Ilkinyldrm/Cyclistic_Case_Study/blob/main/Tableau%20images/Total%20Rides%20Of%20Members%20And%20Casual%20Riders%20by%20The%20Hour%20Of%20The%20day..png)


![data visualisation](https://github.com/Ilkinyldrm/Cyclistic_Case_Study/blob/main/Tableau%20images/Bike%20Types%20Pie%20Chart.png)


![data visualisation](https://github.com/Ilkinyldrm/Cyclistic_Case_Study/blob/main/Tableau%20images/Bike%20Type%20for%20member_casual.png)


![data visualisation](https://github.com/Ilkinyldrm/Cyclistic_Case_Study/blob/main/Tableau%20images/Ride%20Length%20Minutes%20by%20Bike%20Type.png)


![data visualisation](https://github.com/Ilkinyldrm/Cyclistic_Case_Study/blob/main/Tableau%20images/Start%20Station%20Rides.png)


![data visualisation](https://github.com/Ilkinyldrm/Cyclistic_Case_Study/blob/main/Tableau%20images/End%20Station%20Rides%20.png)

## Act
### Conclusion
The analysis highlights distinct differences in the behavior and preferences of casual riders and annual members. Members use Cyclistic bikes primarily for commuting, showing consistent patterns in start and end stations, bike types, and weekday usage. Casual riders, on the other hand, demonstrate a preference for recreational use, favoring weekends, tourist areas, and classic bikes.
### Recommendations
1. Offer incentives and promotions to convert casual riders into annual members by highlighting the benefits of regular usage and cost savings.
2. Improve bike availability and maintenance at high-traffic start and end stations, especially weekday for members and weekends for casual riders.
3. Ensure that there are sufficient bikes available at popular stations during peak hours (7:30 AM to 8:30 AM and 4:30 PM to 5:30 PM).
4. Implement seasonal marketing campaigns and promotions to maximize ridership during summer and maintain engagement during winter.
5. Offer trial periods and discounts to encourage casual riders to experience the benefits of electric bikes.
6. Create engaging content (videos, blog posts) showcasing the advantages of electric bikes, such as ease of use, speed, and environmental benefits.

By implementing these detailed recommendations, Cyclistic can effectively enhance the rider experience, increase overall ridership, and drive sustainable growth.
