# COVID-19-Online-Learning-Analysis
DATA MANIPULATION AND DATA VISUALIZATION
COVID-19 Online Learning Analysis Report
By
IMADE CHELSEA

Table of Contents
	COVID-19 Online Learning Data Overview
	Tools
	Exploratory Data Analysis
	Data Cleaning
	Data Processing
	Data Analysis
	Data Visualization
	Insights
	Recommendations

 COVID-19 Online Learning Data Overview
The dataset contains information on online learning engagement metrics across 20 countries over a period of several years, including the COVID-19 pandemic era. It highlights trends, growth rates, and activity volatility, helping us understand the impact of the pandemic on online education adoption globally.
- Period: January 2004 – October 2021
- Countries Covered**: 20
- Metrics: Annual engagement/activity scores
The dataset explores trends in online learning across countries, providing a foundation for analyzing regional engagement, growth patterns, and potential market opportunities during the COVID-19 era. The dataset contains data from 214 rows and 21 columns, with the following details:
Columns Overview:
1.	Month: Represents the time period (monthly data from 2004 onward).
2.	Country Columns: The remaining 20 columns represent online learning activity metrics for various countries (e.g., "Argentina", "Brazil", etc.).
Data Types:
•	Month: Object (likely a date in "YYYY-MM" format).
•	Country Data: Integer values, presumably activity counts or scores.


Tools
The analysis was conducted using:
- Python: For data manipulation, analysis, and visualization
- Libraries: 
  - Pandas for data processing
  - Matplotlib, Plotly express and Seaborn for visualizations


Exploratory Data Analysis
Key Observations:
- Data includes monthly engagement metrics for each country.
- There are no missing values; all 214 rows and 21 columns are complete.
- Metrics vary significantly across countries, with some showing steady trends and others experiencing sharp fluctuations.


 Data Cleaning
- Date Conversion: The `Month` column was converted to datetime format to enable time-series analysis.
- ![image](https://github.com/user-attachments/assets/f4584cc3-b901-4044-8239-76a7abb36559)

 

 Data Processing
- Computed metrics:
  - Total Activity: Summation of all engagement scores for each country.
  - Growth Rate: Percentage change in engagement from the first to the last period.
  - Volatility: Standard deviation of activity over time.
- Extracted top-performing countries for further trend analysis.

 Data Analysis
Key Metrics:
- Top Performers by Total Activity:
  1. United States (10,698)
  2. Germany (8,715)
  3. United Kingdom (8,662)
  4. India (6,220)
  5. Spain (5,554)
  


- Growth Rates:
  - Negative growth trends were observed in most countries, with the United States and India showing significant declines (-57.3% and -65.9%, respectively).
  - ![image](https://github.com/user-attachments/assets/aabf118c-b600-43c3-94cc-de988208d885)
![image](https://github.com/user-attachments/assets/10962b4f-c29c-4f7d-84cd-ac1170f13315)

 
 
  
- Volatility:
  - High volatility was observed in the Philippines, India, and Spain, indicating inconsistent engagement patterns.


 Data Visualization
- Trend Analysis:
  Line plots revealed fluctuations in engagement for the top-performing countries, with consistent activity in Germany and the UK and declining trends in India and Spain.
![image](https://github.com/user-attachments/assets/178f6471-23cf-4ff1-b195-5d42061f2143)
![image](https://github.com/user-attachments/assets/f50eee6a-0c10-4cea-b301-bab76569b825)

 
 --------------------------------------------------------------------------------------------------------------------------------------
 
 ![image](https://github.com/user-attachments/assets/7287aa53-01ff-44b2-9955-153b5f4a07b8)
 ![image](https://github.com/user-attachments/assets/03869382-0bc4-4074-86ce-200fb5fa5c54)


  
- Volatility Patterns:
  Bar charts highlighted countries with the highest volatility, emphasizing regions with irregular engagement.
   ![image](https://github.com/user-attachments/assets/843dc63c-4791-418b-8004-5c1567c4b1b2)
  ![image](https://github.com/user-attachments/assets/79628a2a-9113-4a78-b773-0c2837abf85f)


 
- Total Activity:
  A horizontal bar chart displayed the total engagement across all countries, showcasing the dominance of the US, Germany, and the UK.
  ![image](https://github.com/user-attachments/assets/8ea1a563-ed65-45b4-a685-a07f29297ac6)
![image](https://github.com/user-attachments/assets/048b6cdc-e554-40f7-abc2-f917a89b8a49)

 
 

 Insights
1. Regional Engagement
   - The US, Germany, and the UK lead in total activity, underscoring the prominence of online learning in these regions.
2. Declining Trends:
   - Many countries, including India and Spain, show declining activity over time, potentially linked to pandemic recovery or user fatigue.
3. Volatility:
   - Countries like the Philippines exhibit high engagement spikes, suggesting a need for stable content strategies.
 



Recommendations
1. Revitalize Declining Countries
   - Introduce localized campaigns and tailored content for India, Spain, and the US to counteract declining trends.
2. Capitalize on Stability:
   - Monetize the consistent user base in Germany and the UK through premium features and certifications.
3. Address Volatility:
   - Investigate engagement spikes in volatile markets like the Philippines and create strategies to sustain interest.
4. Explore Emerging Markets:
   - Run awareness campaigns in underperforming but stable regions like South Africa and Poland.



