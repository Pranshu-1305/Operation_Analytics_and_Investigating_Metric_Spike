# Operation_Analytics_and_Investigating_Metric_Spike
**Case Study 1: Job Data Analysis**
Project Description:
This case study focuses on analyzing job data from a crowdsourced job review platform. The aim is to examine how jobs are reviewed, the time taken, language distribution, and duplication within the dataset. These insights help improve platform performance, fairness, and workload optimization.
Approach:
We used structured SQL queries on the job_data table. The analysis was broken into four parts:
1.	Jobs Reviewed Over Time – Review pattern across hours for each day in November 2020.
2.	Throughput Analysis – Daily and 7-day rolling throughput (events per second).
3.	Language Share Analysis – Identify which languages dominate job reviews in the last 30 days.
4.	Duplicate Row Detection – Spot any duplicated job entries that may affect insights.
 Tech-Stack Used:
•	MySQL Workbench 8.0 – For running SQL queries and visualizing results.
 Insights:
•	Majority of jobs were reviewed between 9 AM and 1 PM.
•	Throughput varied across days but smoothed out well in the 7-day average.
•	English and Hindi were the most reviewed languages.
•	Duplicate rows (~0.8%) existed and were mainly from manual data entries.
Result:
The analysis surfaced key inefficiencies and data patterns in job reviews. It helped in planning reviewer schedules and deciding which languages need more human resources. The rolling throughput metric was more stable and insightful than daily fluctuations.
**Case Study 2: Investigating Metric Spike**
Project Description:
This project aims to analyze user behavior, growth, retention, and email engagement patterns for a digital product. By examining weekly trends and engagement at both user and device levels, the project provides a comprehensive understanding of how users interact with the product and respond to email campaigns.
The purpose of this analysis is to:
•	Monitor user activity and growth trends.
•	Identify retention performance by weekly cohorts.
•	Evaluate how users interact with emails (open rate, clickthrough rate, etc.).
•	Provide actionable insights for product and marketing teams.
Approach:
We broke the project into five major parts:
1.	Weekly User Engagement – To track how active users are each week.
2.	User Growth Analysis – To see how many new users are joining weekly.
3.	Weekly Retention Analysis – To observe how many users return in future weeks after signup.
4.	Device-wise Weekly Engagement – To track usage patterns based on device types.
5.	Email Engagement Analysis – To find open and click-through behavior in emails.
We used USERS, EVENTS and EMAIL_EVENT tables to derive the above insights using weekly aggregations and cohort analysis.
Tech-Stack Used:
•	MySQL Workbench 8.0 – For writing and executing SQL.
Insights:
•	Weekly user activity peaked around Week 20, possibly due to a new feature launch.
•	Growth stagnated after Week 24, suggesting a need for re-engagement strategies.
•	Only ~21% of users were retained after 3 weeks.
•	Most users used "Acer Aspire Notebook" and "Dell Inspiron Desktop" for accessing the platform.
•	Email open rates were decent (~31%), but click-through rate was low (~10.5%).
Result:
The study provided a strong foundation for decision-making in both marketing and product teams. Based on this, reactivation campaigns can be targeted, device support decisions can be improved, and email content strategies can be revisited for higher engagement.

The study provided a strong foundation for decision-making in both marketing and product teams. Based on this, reactivation campaigns can be targeted, device support decisions can be improved, and email content strategies can be revisited for higher engagement.
