 

                                                       Data-Driven Analysis of Social Media Users
## Project Overview

     This project analyzes social media user behavior using a synthetic Instagram dataset containing demographic, lifestyle, health, engagement, and security attributes. The objective is to uncover usage patterns, user engagement levels, and behavioral trends through data-driven analysis. Interactive dashboards are used to visualize insights and support user segmentation and comparative analysis. The project demonstrates how synthetic data can be effectively used for learning and analytics without compromising privacy.

**Project Objectives**

    To analyze Instagram user behavior using data-driven techniques. 
   -   To study user engagement patterns and daily usage behavior.  
   -   To explore relationships between lifestyle, health indicators, and social media usage.  
   -   To assess user security practices such as privacy settings and authentication methods.  
   -   To segment users based on engagement, lifestyle, and security levels.  
   -   To design an interactive dashboard for effective data visualization and insight discovery

**Data Sources**
          Sources : Raw Data
[https://www.kaggle.com/datasets/rockyt07/social-media-user-analysis](https://www.kaggle.com/datasets/rockyt07/social-media-user-analysis)
Domin : Social Media

## Problem​​ Statement

        With the rapid growth of social media platforms, understanding user behavior has become essential for improving user experience, digital well-being, and platform security. However, analyzing real user data raises privacy and ethical concerns. This project addresses the challenge of understanding social media user behavior by using a large-scale synthetic dataset that simulates realistic Instagram usage patterns. The aim is to analyze user behavior across multiple dimensions such as demographics, lifestyle, health, engagement, security, and usage trends, and present insights through interactive visual analytics.
        
## 📋 Demographics & Background – Attribute Details

| Column Name | Description | Purpose / Usage |
|------------|------------|-----------------|
| User_ID | Unique identifier assigned to each user | Used to uniquely identify and track individual users |
| App_Name | Name of the social media application (Instagram) | Used to distinguish platform-specific analysis |
| Age | Age of the user in years | Used for age-based behavior and engagement analysis |
| Gender | Gender identity of the user (Male, Female, Non-binary, etc.) | Enables gender-wise comparison of usage and engagement |
| Country | Country of residence | Supports geographic and regional analysis |
| Urban_Rural | Indicates whether the user lives in an urban or rural area | Used to compare digital behavior across locations |
| Income_Level | Economic status of the user (Low, Middle, High) | Helps analyze engagement and premium feature adoption |
| Employment_Status | Employment condition (Employed, Student, Unemployed, etc.) | Used to study usage patterns based on work status |
| Education_Level | Highest educational qualification attained | Helps assess awareness and security adoption |
| Relationship_Status | User’s relationship or marital status | Used to analyze communication and engagement behavior |
| Has_Children | Indicates whether the user has children (Yes/No) | Helps understand lifestyle balance and time spent |

## 🏃‍♂️ Lifestyle & Health – Attribute Details

| Column Name | Description | Purpose / Usage |
|------------|------------|-----------------|
| User_ID | Unique identifier for each user | Used to link lifestyle and health data with other user tables |
| Exercise_Hours_Per_Week | Total hours spent on physical exercise per week | Used to assess physical activity level |
| Sleep_Hours_Per_Night | Average number of sleep hours per night | Used to evaluate sleep adequacy and quality |
| Diet_Quality | Categorical indicator of diet habits (Poor, Average, Good) | Helps analyze nutrition-related lifestyle patterns |
| Smoking | Smoking status of the user (Yes / No / Former) | Used to assess health risk behavior |
| Alcohol_Frequency | Frequency of alcohol consumption | Helps evaluate lifestyle risk factors |
| Perceived_Stress_Score | Self-reported stress level score | Used to identify stress intensity |
| Self_Reported_Happiness | Self-reported happiness score | Used to assess mental well-being |
| Body_Mass_Index | BMI value calculated from height and weight | Used to classify weight categories |
| Blood_Pressure_Systolic | Systolic blood pressure value | Used to assess cardiovascular risk |
| Blood_Pressure_Diastolic | Diastolic blood pressure value | Used to assess cardiovascular health |
| Daily_Steps_Count | Average number of steps taken per day | Used to measure daily physical activity |
| Sleep_Quality | Categorized sleep quality (Poor / Average / Good) | Derived from sleep duration and habits |
| Diet_Quality_Score | Numeric score representing diet quality | Used for lifestyle score calculations |
| Lifestyle_Level | Categorized lifestyle classification (Low / Moderate / High) | Used for segmentation and comparison |
| Lifestyle_Score | Composite score calculated from multiple lifestyle indicators | Used to evaluate overall lifestyle health |
| High_Stress_Flag | Indicator showing whether user has high stress (Yes / No) | Used to identify at-risk users |
| Age_Group | Categorized age range derived from Age | Enables simplified age-based segmentation |
| Adult_Flag | Indicates whether the user is an adult (Yes/No) | Used for age-based classification and filtering |
| Parent_Status | Indicates whether the user is a parent | Derived from Has_Children for easier analysis |     

## 📅 Daily & Weekly Lifestyle – Attribute Details

| Column Name | Description | Purpose / Usage |
|------------|------------|-----------------|
| User_ID | Unique identifier for each user | Used to link work–life data with other user tables |
| Weekly_Work_Hours | Total number of working hours per week | Used to assess workload and work intensity |
| Hobbies_Count | Number of hobbies the user actively engages in | Indicates leisure and personal interests |
| Social_Events_Per_Month | Number of social events attended per month | Used to measure social interaction level |
| Books_Read_Per_Year | Number of books read in a year | Reflects intellectual and personal development |
| Volunteer_Hours_Per_Month | Time spent on volunteering activities per month | Indicates social contribution and balance |
| Travel_Frequency_Per_Year | Number of trips taken per year | Used to assess recreational activity |
| Weekly_Work_Hours_Category | Categorized work hours (Low / Moderate / High) | Simplifies analysis of work pressure |
| Daily_Weekly_Lifestyle_Score | Composite score derived from work and lifestyle activities | Used to quantify overall work–life balance |
| Daily_Weekly_Lifestyle_Level | Categorized lifestyle level (Low / Moderate / High) | Used for segmentation and comparative analysis |

## 📸 Instagram Usage & Engagement – Attribute Details

| Column Name | Description | Purpose / Usage |
|------------|------------|-----------------|
| User_ID | Unique identifier for each user | Used to link Instagram usage data with other user datasets |
| Daily_Active_Minutes_Instagram | Total minutes spent on Instagram per day | Used to analyze daily usage intensity |
| Sessions_Per_Day | Number of app sessions per day | Indicates frequency of app usage |
| Posts_Created_Per_Week | Number of posts created per week | Measures content creation behavior |
| Reels_Watched_Per_Day | Number of reels watched daily | Used to analyze short-form content consumption |
| Stories_Viewed_Per_Day | Number of stories viewed per day | Indicates passive content consumption |
| Likes_Given_Per_Day | Number of likes given per day | Measures user interaction level |
| Comments_Written_Per_Day | Number of comments written per day | Indicates active engagement behavior |
| Dms_Sent_Per_Week | Number of direct messages sent per week | Used to analyze communication activity |
| Dms_Received_Per_Week | Number of direct messages received per week | Indicates inbound social interaction |
| Ads_Viewed_Per_Day | Number of advertisements viewed daily | Used to analyze ad exposure |
| Ads_Clicked_Per_Day | Number of advertisements clicked daily | Measures ad engagement |
| Time_On_Feed_Per_Day | Time spent scrolling feed per day (minutes) | Used to analyze feed engagement |
| Time_On_Explore_Per_Day | Time spent on explore page per day (minutes) | Indicates content discovery behavior |
| Time_On_Messages_Per_Day | Time spent on messages per day (minutes) | Measures communication usage |
| Time_On_Reels_Per_Day | Time spent watching reels per day (minutes) | Used to analyze reel consumption |
| Followers_Count | Total number of followers | Used to identify influence and reach |
| Following_Count | Total number of accounts followed | Used to analyze social connectivity |
| Uses_Premium_Features | Indicates whether premium features are used (Yes / No) | Used to analyze monetization behavior |
| Notification_Response_Rate | Percentage of notifications responded to | Measures responsiveness and engagement |
| Average_Session_Length_Minutes | Average duration of each app session | Used to analyze session behavior |
| Content_Type_Preference | Preferred content type (Reels, Posts, Stories) | Used for content personalization analysis |
| Preferred_Content_Theme | Preferred content theme (Lifestyle, Travel, Tech, etc.) | Helps analyze content interest |
| Privacy_Setting_Level | Privacy configuration (Public / Friends_Only / Private) | Used for security and privacy analysis |
| Two_Factor_Auth_Enabled | Indicates if 2FA is enabled (Yes / No) | Used to assess security adoption |
| Biometric_Login_Used | Indicates if biometric login is used (Yes / No) | Used to analyze security behavior |
| Linked_Accounts_Count | Number of linked external accounts | Indicates account connectivity |
| Subscription_Status | Indicates subscription plan (Free / Paid) | Used to analyze user monetization |
| User_Engagement_Score | Composite engagement score | Used to classify engagement level |
| Account_Creation_Year | Year the account was created | Used for time-based trend analysis |
| Last_Login_Date | Most recent login date | Used to analyze recent activity trends |
| Followers_Following_Count_Ratio | Ratio of followers to following | Used to identify influencer-like users |
| Total_App_Usage_Per_Day (Hours) | Total Instagram usage per day in hours | Used for simplified usage analysis |
| Security_Score | Composite score based on security features | Used to evaluate user security strength |
| User_Security_Level | Categorized security level (Low / Moderate / High) | Used for segmentation and filtering |


## 🔧 Data Preprocessing Steps

### 📥 Data Import
- Imported the synthetic Instagram user dataset into **Microsoft Excel** and **Power BI Desktop**.
- Verified column names, data types, and record counts after loading the data.

---

### 🧹 Data Cleaning
- Duplicate records were identified and validated based on the **User_ID** field.
- Data type values were handled appropriately.
- Ensured consistency in categorical values (e.g., gender, privacy settings, subscription status).

---

### 🔄 Data Type Correction
- Converted numerical fields such as **age, usage minutes, followers count, and scores** to appropriate numeric data types.
- Converted date-related fields (**Last_Login_Date**) to date format.
- Standardized boolean fields (Yes / No).

---

### 🧠 Feature Engineering
- Created derived columns such as:
  - **Age_Group**, **Adult_Flag**, **Parent_Status**
  - **Lifestyle_Score**, **Lifestyle_Level**
  - **Daily_Weekly_Lifestyle_Score**, **Daily_Weekly_Lifestyle_Level**
  - **Followers–Following Ratio**
  - **Total App Usage per Day (Hours)**
  - **Security Score** and **User Security Level**
- Normalized time-based metrics by converting **minutes into hours** for better readability.

## 🧩 Categorization & Segmentation

- Categorized continuous variables into meaningful groups such as **engagement levels**, **lifestyle levels**, and **security levels**.
- Created indicator flags including **High Stress**, **Low Activity**, and **Overweight** for risk analysis and segmentation.

---

## 🧱 Data Modeling

- Ensured proper relationships between tables using **User_ID** as the primary key.
- Verified **one-to-one relationships** to support accurate aggregation and filtering across visuals.

---

## ✅ Validation & Quality Checks

- Cross-checked calculated columns and DAX measures for accuracy.
- Validated aggregated results using sample records.
- Ensured visuals responded correctly to **slicers and filters**.

---

## 📊 Analysis & Visualizations

- Analyzed **demographic, usage, lifestyle, health, engagement, and security patterns**.
- **KPI cards** were used to highlight key performance metrics.
- Multiple visualizations were used, including **donut charts, column charts, map views, matrix tables, and line charts**.

---

## 🌟 Highlights

- Analyzed **1M+ synthetic social media user profiles** to understand user behavior comprehensively.
- Explored **demographic, usage, lifestyle, health, engagement, and security patterns**.
- Built derived metrics such as **Lifestyle Score**, **Engagement Level**, **Security Score**, and **Usage Hours**.
- Identified **highly engaged users and top influencers** based on follower count.
- Analyzed **security adoption**, including two-factor authentication, biometric login, and privacy settings.
- Visualized **usage and engagement trends over time** using account creation year.
- Designed an **interactive Power BI dashboard** for data-driven analysis.
- Ensured **ethical and privacy-safe analysis** using fully synthetic data.
- Applied **data preprocessing, DAX calculations, and feature engineering** to generate accurate insights.

---

## ✅ Conclusion

This project successfully demonstrated how data-driven analysis can be used to understand social media user behavior using a large-scale synthetic dataset. By analyzing demographic characteristics, usage patterns, lifestyle and health indicators, engagement levels, and security practices, the project provided meaningful insights into how different factors influence user behavior on social media platforms.

The use of **interactive visualizations and KPI-driven dashboards** enabled effective exploration and comparison across multiple user segments. The project also highlighted the importance of **data preprocessing, feature engineering, and proper data modeling** in ensuring accurate and reliable analysis.

Since the dataset is fully synthetic, the analysis was conducted in a **privacy-safe and ethical manner**, making it suitable for learning, research, and dashboard development. Overall, this project demonstrates the practical application of data analytics tools and techniques to extract actionable insights and support informed decision-making in the context of digital behavior analysis.


                                                   
