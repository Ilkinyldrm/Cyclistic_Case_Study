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
![data visualisation](https://github.com/Ilkinyldrm/Cyclistic_Case_Study/blob/main/Tableau%20images/Bike%20Types%20Pie%20Chart.png)
![data visualisation](https://github.com/Ilkinyldrm/Cyclistic_Case_Study/blob/main/Tableau%20images/Bike%20Type%20for%20member_casual.png)
![data visualisation](https://github.com/Ilkinyldrm/Cyclistic_Case_Study/blob/main/Tableau%20images/Ride%20Length%20Minutes%20by%20Bike%20Type.png)
![data visualisation](https://github.com/Ilkinyldrm/Cyclistic_Case_Study/blob/main/Tableau%20images/Start%20Station%20Rides.png)
![data visualisation](https://github.com/Ilkinyldrm/Cyclistic_Case_Study/blob/main/Tableau%20images/End%20Station%20Rides%20.png)
## Act
### Conclusion
In conclusion, the analysis of the data reveals interesting insights about the bike usage patterns. Electric bikes emerge as the most popular bike type, with regular bikes following closely behind. Casual riders tend to have longer rides on average compared to annual members. Moreover, annual members demonstrate higher ride frequencies on weekdays, while casual riders display higher ride frequencies on weekends. There is a consistent trend of higher ride counts during the warmer months, with August being the peak month for annual members and July for casual riders. Additionally, both groups exhibit peak ridership between 4 pm and 6 pm, with 5 pm recording the highest number of rides. These findings suggest a shared preference for biking during the late afternoon among both annual members and casual riders.
### Recommendations
To convert casual riders into annual members, here are my recommendations:
1. Offer Trial Memberships: Provide short-term trial memberships at a discounted rate or with additional perks to allow casual riders to experience the benefits of being an annual member.
2. Improve User Experience: Continuously enhance the user experience for annual members, ensuring that they have a seamless and enjoyable riding experience. This includes convenient booking processes, reliable bikes, and excellent customer support.
3. Target Seasonal Riders: Identify casual riders who use the service frequently during peak seasons and offer targeted promotions or discounted rates to encourage them to become annual members.
4. Incentivize Long-Term Commitment: Create incentives for long-term commitment, such as offering discounted rates for multi-year memberships or rewarding loyal members with exclusive rewards and privileges.
5. Gather Feedback and Adapt: Continuously seek feedback from casual riders who have become annual members to understand their needs and preferences better. Adapt membership offerings and benefits accordingly to improve the conversion rate and retention of casual riders as annual members.

By implementing these recommendations, it is possible to attract more casual riders and successfully convert them into loyal annual members, ultimately growing the customer base and promoting long-term engagement with the bike-sharing service.
