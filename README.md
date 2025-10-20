# Facebook Ad Analysis

## Project Overview
This project presents a comprehensive analysis of Facebook advertisement data to uncover insights about audience behavior, ad performance, and spending efficiency.  
The analysis helps understand how factors like age, gender, impressions, and clicks affect ad performance metrics such as cost per click (CPC) and conversion rate.

## Objective
The main objective of this project is to *analyze and visualize Facebook ad campaign data* to identify:
- Which demographic segments respond best to ads  
- How ad spending correlates with conversions  
- Which features most influence click and impression performance  

No predictive modeling was performed — the project focuses purely on *exploratory data analysis (EDA)* and *data-driven insights*.

---

## Dataset
- *Source:* [Kaggle - Facebook Ad Campaign Dataset](https://www.kaggle.com/datasets/madislemsalu/facebook-ad-campaign)  
- *Description:* The dataset contains records of ad campaigns with fields such as:
  - ad_id: Unique identifier for each ad  
  - age: Target age group of users  
  - gender: Gender category targeted by the ad  
  - impressions: Number of times an ad was displayed  
  - clicks: Number of times an ad was clicked  
  - spent: Amount spent on the ad campaign  
  - total_conversion: Total number of conversions from the ad  

---

## Tools & Libraries
The analysis was performed using *Python* and the following key libraries:
- pandas – Data cleaning and manipulation  
- numpy – Numerical computations  
- matplotlib – Data visualization  
- seaborn – Statistical visualizations  

---

## Key Steps
### 1. Data Loading & Inspection
- Imported and explored the dataset.  
- Checked for missing values, duplicates, and data consistency.  

### 2. Data Cleaning
- Handled missing or inconsistent entries.  
- Converted data types where required.  
- Removed outliers to ensure better visualization accuracy.  

### 3. Exploratory Data Analysis (EDA)
- Analyzed distributions of key variables.  
- Studied relationships between impressions, clicks, and spending.  
- Computed and visualized metrics like:
  - *CTR (Click-Through Rate):* CTR = (Clicks / Impressions) * 100  
  - *CPC (Cost Per Click):* CPC = Spent / Clicks  
  - *Conversion Rate:* Conversions / Clicks  
- Explored demographic factors (age and gender) and their impact on performance.  

### 4. Insights & Findings
- Identified cost-efficient ad groups.  
- Determined which demographic segments responded best.  
- Observed ad efficiency trends across different spending levels.  

---

## Results & Insights
- Certain *age groups* show a higher conversion efficiency relative to ad spend.  
- *Gender-based targeting* impacts overall ad engagement rates.  
- Beyond certain spending levels, *conversion growth plateaus*, indicating diminishing returns.  
- Visualizations reveal the correlation between *impressions, clicks, and conversions* clearly.  

---
## Credits

- Developed by: Giddaluru Divya

- Dataset Source: Kaggle – Facebook Ad Campaign Dataset
  
