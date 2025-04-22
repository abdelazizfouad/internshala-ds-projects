# Fitbit Fitness Tracker Case Study

## Motive

The goal of this case study is to analyze Fitbit fitness tracker data to provide marketing and business solutions to WeFit and its subsidiaries. By understanding customer trends, usage patterns, and activity data, we aim to help WeFit optimize its offerings and grow its business across multiple divisions, including **LeanFit**, **FitWear**, and **Sleepy-Nights**.

---
## Company Background

WeFit is a fitness brand that offers a wide range of services including personalized diet plans, fitness gear, apps, and virtual classes. The company was founded by Rohit and Anjali Shah and has grown into a unicorn, achieving a valuation of over $1 billion. It offers a variety of health and fitness solutions, from gym services to custom diet plans and fitness tracking apps. 

---
## Problem Scenarios

### 1. **LeanFit: Targeting Customers for Weight Loss Diet Plans**
   - **Objective**: Identify potential customers who are likely to buy personalized weight loss diet plans.
   - **Factors**: Age, gender, BMI, heart rate, and activity levels (active, moderately active, light activity).
   - **Approach**: Analyze fitness tracker data, focusing on BMI, heart rate, and activity levels to identify individuals who may benefit from a weight loss diet plan.
In addition, the team is asked to create a dashboard to present key metrics and insights, leveraging Fitbit fitness tracker data.

### 2. **FitWear: Identifying Customers for Fitness Gear**
   - **Objective**: Identify customers who are likely to purchase fitness gear, based on their activity levels.
   - **Criteria**:
     - **Active Users**: Wearing the gear for more than 20 days and recording an average of more than 30 very active minutes.
     - **Potential Fitness Enthusiasts**: Wearing gear for more than 20 days with over an hour of fairly active minutes.
   - **Approach**: Analyze fitness tracker data to categorize users into active or beginner fitness enthusiasts who may be interested in purchasing fitness gear.

### 3. **Sleepy-Nights: Targeting Customers for Sleep Scheduling App**
   - **Objective**: Identify customers who struggle with maintaining proper sleep schedules.
   - **Factors**: Sleep patterns, time spent in bed vs. sleep, irregular sleep schedules.
   - **Approach**: Analyze Fitbit data to find customers exhibiting signs of sleep deprivation or irregular sleep schedules, targeting them for Sleepy-Nights' sleep scheduling app.

### 4. **WeFit Dashboard**
   - **Objective**: Create an interactive dashboard that visualizes key metrics for customer activity, distance traveled, calories burned, and other related data.
   - **Approach**: Use daily activity data to perform the following tasks:
     - Find unique user IDs.
     - Calculate the number of days each user tracks their activity.
     - Categorize users into active, moderate, and light users.
     - Group users into Pro, Intermediate, or Beginner based on their mean distance traveled.
     - Calculate total steps, calories burned, and active minutes.

---
## Data Used


The dataset used in this case study is the **FitBit Fitness Tracker Data**, downloaded from Kaggle, which contains minute-level data on physical activity, heart rate, and sleep monitoring from Fitbit users. The data includes:

- **Respondent activity**: Minute-level output for activity, heart rate, and sleep monitoring.
- **Data generation period**: 03.12.2016 - 05.12.2016, collected from 30 eligible Fitbit users.

--- 

## Tools Used

- **Data Analysis**: Microsoft Excel
- **Visualization**: Microsoft Excel (Charts and PivotTables)
