# Netflix-Database-Insights-Summary-Report
The goal of this analysis is to understand the demographic and usage patterns of Netflix users, calculate key metrics such as Lifetime Value (LTV), and provide insights based on various attributes such as age, country, device usage, and subscription types.

## **Data**

The dataset contains the following columns:

•	**User ID**: A unique identifier for each user.

•	**Subscription Type**: The type of subscription plan (Basic, Standard, Premium).

•	**Monthly Revenue**: The monthly revenue generated from each user.

•	**Join Date**: The date the user joined Netflix.

•	**Last Payment Date**: The date of the last payment made by the user.

•	**Country**: The country of the user.

•	**Age**: The age of the user.

•	**Gender**: The gender of the user.

•	**Device**: The primary device used by the user (Smartphone, Tablet, Smart TV, Laptop).

•	**Plan Duration**: The duration of the subscription plan.
## **Metrics and Analyses**

1.	**Number of Users per Country**

The highest number of users are from the United States and Spain, each with 451 users, making up 18.04% of the total user base each. Following these are Canada with 317 users (12.68%), and the United Kingdom with 183 users (7.32%). Australia, Germany, France, Brazil, Mexico, and Italy each have the same number of users, 183, accounting for 7.32% of the total user base per country.

![image](https://github.com/user-attachments/assets/d19c1385-3dc6-4511-a78c-7ec5c43c4c9a)
![image](https://github.com/user-attachments/assets/bb8ec719-e150-4534-ab48-3b1e3e763ad8)

2.	**Gender Counts**

The overall gender distribution among users is almost equal, with 1257 female users (50.28%) and 1243 male users (49.72%).
The gender distribution is almost equal across all countries, with a nearly balanced ratio of female and male users in each country. For example, in the United States, the distribution is 49.89% female and 50.11% male, and in Spain, it is 51.66% female and 48.34% male, reflecting a similar balance in other countries as well.
![image](https://github.com/user-attachments/assets/5631012f-34e7-4bd0-b7bf-6ec9e8226629)
![image](https://github.com/user-attachments/assets/cc2889b8-9f10-46ee-a308-9e528917ddba)

3.	**Device Counts**

The distribution of devices among users is relatively balanced. The breakdown is as follows:

- Laptops are used by 636 users (25.44%).
- Tablets are used by 633 users (25.32%).
- Smartphones are used by 621 users (24.84%).
- Smart TVs are used by 610 users (24.40%).
![image](https://github.com/user-attachments/assets/39170af2-d6e7-4962-9bad-43dbae55f236)
4.	**Subscription Type Counts**

The distribution of subscription types among users is as follows:

- **Basic:** 999 users (39.96%)
- **Standard:** 768 users (30.72%)
- **Premium:** 733 users (29.32%)
![image](https://github.com/user-attachments/assets/153da09a-131d-4289-80bf-0aa220bc35cc)
5.	**Age Distribution**

The age distribution of users shows the following statistics:

•	**Mean Age:** 38.8 years

•	**Median Age:** 39.0 years

•	**Minimum Age:** 26 years

•	**Maximum Age:** 51 years

•	**Standard Deviation:** 7.17 years

•	Most Common Ages:

•	30 years: 116 users

•	39 years: 116 users
![image](https://github.com/user-attachments/assets/0249edc2-4cef-4584-ae1f-76b89997bf0d)
6.	**Duration Between Join Date and Last Payment Date**

The duration between the join date and the last payment date among users shows the following statistics:

•	**Mean Duration:** 308.6 days

•	**Median Duration:** 307.0 days

•	**Minimum Duration:** 8 days

•	**Maximum Duration:** 655 days

7.	**Lifetime Value (LTV)**

The highest total LTV is in the United States, with an LTV of 60,445, accounting for 18.91% of the overall LTV. This is because the United States has the highest number of users. Similarly, Spain has a high total LTV of 59,269 (18.54% of the overall LTV) due to its large user base. Other countries, such as Canada and France, have total LTVs of 43,116 (13.48%) and 26,080 (8.16%) respectively. The total LTVs for the remaining countries, including Australia, Brazil, Germany, Italy, Mexico, and the United Kingdom, range between 23,618 and 25,990, each contributing between 7.38% and 7.84% to the overall LTV.
![image](https://github.com/user-attachments/assets/06fc001e-9533-4525-aab4-382738b7c585)
The average Lifetime Value (LTV) per user varies across different countries. France has the highest average LTV at 142.51, followed closely by the United Kingdom at 142.02. Other countries with relatively high average LTVs include Australia (136.73), Brazil (136.50), and Canada (136.01). The United States, despite having the highest total LTV due to its large user base, has an average LTV of 134.02.

Countries like Germany (133.05), Mexico (132.39), and Spain (131.42) have average LTVs that are slightly lower, while Italy has the lowest average LTV at 129.06.

This analysis highlights that while the United States and Spain have high total LTVs due to their large user bases, countries like France and the United Kingdom lead in terms of average LTV per user.
![image](https://github.com/user-attachments/assets/93f5db9d-f4b0-49b2-a3b5-20ca836ebfd9)

**Recommendations**

1.	**Focus on High-LTV Countries:**

•	The United States and Spain have the highest total LTVs. Consider targeted marketing and retention strategies in these countries to maximize revenue.

•	France and the United Kingdom, with the highest average LTVs, should also be prioritized for premium offerings and upsell opportunities.

2.	**Gender-Specific Campaigns:**

•	The gender distribution is nearly equal across all countries. Tailor marketing campaigns to address the preferences and needs of both male and female users equally.

•	Utilize the balanced gender ratio to create inclusive content and promotions that appeal to a wide audience.
3.	**Device Optimization:**

•	With a relatively even distribution of devices used by subscribers (Laptops, Tablets, Smartphones, Smart TVs), ensure that the platform is optimized for all these devices.

•	Develop device-specific features or promotions to enhance user experience and engagement.

4.	**Subscription Type Promotions:**

•	The Basic subscription type has the highest number of users. Consider introducing features or benefits to encourage upgrades to Standard or Premium plans.

•	Implement targeted promotions to highlight the value of higher-tier subscriptions to Basic plan users.

5.	**Future Analysis**:

•	Conduct deeper analyses on user behavior, content preferences, and churn rates to refine marketing and retention strategies.

•	Explore geographical trends and regional preferences to tailor content and offerings to different markets.

