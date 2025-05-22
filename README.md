![SoundStream Logo Design](https://github.com/user-attachments/assets/d99d142b-f8af-4a55-a903-0c0cf7116914)

# About Soundstream
Soundstream is a fictional music streaming platform that offers users a vast library of songs, playlists, and podcasts. The service operates on a freemium model, with free users supported by ads and premium subscribers enjoying ad-free listening and additional features. This project emulates typical data challenges faced by platforms like Soundstream, such as understanding user engagement, improving retention, and increasing subscription rates.

# Key Objectives
- Understand user actions and engagement patterns
- Analyze user retention and churn rates
- Simulate business scenarios to inform decision-making
- Build interactive dashboards and visualizations

# Data Overview
The Data set includes: [Soundstream User Data](https://docs.google.com/spreadsheets/d/1TR00FBtwcWj_LmTFnyHPbtUGRQBMvthY4Ngwf0t0kDs/edit?usp=sharing)
- Columns:
   - user_id: Unique identifier for users
   - sign_update: User signup date
   - action: User activity (ex:upgrade, create a playlist, etc)
   - timestamp: Event time
   - subscriptioin_type: Free or premium subscription
   - device: User device (ex: mobile, desktop, etc)
   - monthly_revenue: Revenue generated from premimum users
 

# Tools Used
# Google Sheets: [Insights](https://docs.google.com/spreadsheets/d/1FU8dilTC9TzEKuNTXGFGjlhvHGWLE-kQgXxHxbm84D4/edit?usp=sharing)
 - Cleaned and structed raw data
 -  Created Pivot tables and analyzed key metrics (ex; Revenue, User Activity, etc)

# Bigquery
 - Queried the dataset to identify trends:
    - [Popular actions](https://console.cloud.google.com/bigquery?ws=!1m7!1m6!12m5!1m3!1snth-glass-457514-s4!2seurope-west1!3see38bd2c-e7a5-46b0-a0d1-436de45f6d13!2e1)
    - [Average number of user sessions](https://console.cloud.google.com/bigquery?ws=!1m7!1m6!12m5!1m3!1snth-glass-457514-s4!2seurope-west1!3s46cf1ae1-8891-40bb-a7e0-dc53823072f2!2e1)
    - [Days Inactive](https://console.cloud.google.com/bigquery?ws=!1m7!1m6!12m5!1m3!1snth-glass-457514-s4!2seurope-west1!3s98271282-3b75-4a25-88a9-cc624a68f131!2e1)
    - [User Segmentation by Suscrption](https://console.cloud.google.com/bigquery?ws=!1m7!1m6!12m5!1m3!1snth-glass-457514-s4!2seurope-west1!3sc2e23080-efce-43ed-ac15-d46dfc3bc63f!2e1)

# Python
  - Filtered and Analyzed data for advanced metrics
  - Visualized user retention and simulated scenarios (eg, increased upgrades)

# Amplitude [Soundstream Dashboard](https://app.eu.amplitude.com/analytics/muddy-wildflower-011456/dashboard/e-wtijwfgf?source=copy+url)
 - Imported procssed data for event tracking
 - Analyzed user flows and retention metrics

# Looker Studio
 - [Built interactive dashboards](https://lookerstudio.google.com/reporting/f263c661-d2f6-4d74-a0ec-3868d0d32870):
   - Monthly trends in user actions
   - Subscription-based Segmentation
   - Age Group Segmentation
   - Retention Analysis

# Key Insights
  - User Actions: Most common user activity is upgrade_premium, followed by like_song
    
![Top Actions Performed](https://github.com/user-attachments/assets/10c69b9a-535e-41a6-be9e-a761644cfb2c)

 - Retention Trends: Day-1 retention rate at 40%, with a signifcant drop-off by Day-7
   
![Retention Rates over time](https://github.com/user-attachments/assets/b406e5ae-2e8d-430f-b0c8-9783f6494340)

 - Churn Rate: Identified users inactive for 30+ days as churned

![Active vs Churned Users](https://github.com/user-attachments/assets/23a285a0-fd26-4190-93d7-63205901f425)


# Revenue Simulation
  - 50%, 75% and 100% free-to-premium user upgrades

![Revenune Simulation](https://github.com/user-attachments/assets/2f0122eb-f6e5-4fbd-9c71-01a94ccd4c71)

  - 5% and 10% retention improvement

![Retention Improvement](https://github.com/user-attachments/assets/2fe33c3e-d7a1-41f2-8c84-5f1e7bd8aae8)

# Future Improvements
 - Enhance user segmentation by adding demographic data.
 - Incorporate machine learning for predictive analytics.
 - Expand the dataset to include more detailed event logs.

# Closing Statement
This project provides a comprehensive exploration of user behavior and business metrics for Soundstream, leveraging various analytical tools to derive actionable insights. By understanding user actions, retention, and revenue, we’ve simulated potential strategies to improve business performance.

Future improvements, such as integrating demographic data, applying machine learning for predictive analytics, and expanding the dataset with more detailed event logs, could further enhance the depth and scope of these analyses. These steps will ensure a more refined understanding of user behavior and empower data-driven decision-making for platforms like Soundstream.




 




