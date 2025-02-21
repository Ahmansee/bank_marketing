# bank_marketing
The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe a term deposit (variable y).

## Purpose of Analysis:
The purpose of the analysis is to **predict whether a client will subscribe to a term deposit (variable y)** based on the data related to direct marketing campaigns conducted through phone calls by a Portuguese banking institution. The ultimate goal is to improve the effectiveness of the bank's marketing campaigns by targeting the right customers, thereby increasing the success rate of subscriptions and optimizing resource allocation.

## Data Sources:
- <a href="https://archive.ics.uci.edu/dataset/222/bank+marketing">data source</a>
- <a href="https://github.com/Ahmansee/bank_marketing/blob/main/bank.csv">bank_data1</a>
- <a href="https://github.com/Ahmansee/bank_marketing/blob/main/bank-full.csv">bank_data2</a>
- <a href=""></a>
- <a href=""></a>


## Questions for more insight:
1.How do client demographics (e.g., age, job, education) influence the likelihood of subscribing to a term deposit?
2.Does the duration of the last contact (phone call) have a significant impact on the outcome? 
3.Are there seasonal or temporal patterns (e.g., month, day of the week) that affect subscription rates?
4.How does the outcome vary based on the number of contacts performed during the campaign?
5.Are there any missing or inconsistent values in the dataset? How will they be handled?

## Analysis Methodology,Data Cleaning & Transformation:
1. Load the dataset into Power BI and ensure the "age" column is clean and properly formatted.  
2. Used a bar chart to show subscription rates by age group.  
3. Added a slicer to dynamically explore subscription rates across age groups.  
4. Observed that the 40-50 age group has the highest subscription rate.  
5. Ensured that the "job" column is clean and properly categorized.  
6. Used a stacked bar chart or pie chart to show subscription rates by job category.  
7. Compared subscription rates between high-income and low-income job categories using filters or slicers.  
8. Observed that high-income professionals have higher subscription rates.  
9. Ensure the "education" column is clean and properly categorized.  
10. Created a new column to group education levels (e.g., "university degree," "high school") using DAX.  
11. Used a bar chart or column chart to show subscription rates by education group.  
15. Ensured that the "duration" column is clean and properly formatted. 

## Results:
1.Middle-aged clients (40-50) are more likely to subscribe because they typically have higher savings and financial 
2.stability compared to younger clients (20-30), who may have lower disposable income.  
2. High-income professionals (e.g., managers, engineers) are more likely to subscribe than low-income or unstable job holders (e.g., students, blue-collar workers) because they have more financial resources.  
3. Highly educated clients are more likely to subscribe because they are more financially literate and aware of investment opportunities.  
4. Longer call durations correlate with higher subscription rates because interested clients engage more, but this could also be a result of the outcome (interested clients stay longer).  
7. Weekdays (Tuesday, Wednesday) have higher subscription rates than weekends because clients are more available and engaged during workdays.  
8. Calls during working hours (10 AM - 4 PM) are more successful because clients are more likely to answer and engage during these times.  
 
## Conclusion:
The analysis shows that middle-aged clients (40-50) are more likely to subscribe to term deposits due to their financial stability, while younger clients (20-30) with lower disposable income are less likely. High-income professionals (e.g., managers, engineers) and highly educated individuals show higher subscription rates because they have more resources and financial awareness. Longer call durations correlate with higher subscriptions, but this should be used cautiously due to ethical concerns. Campaigns are more successful on weekdays (especially Tuesday and Wednesday) and during working hours (10 AM - 4 PM). Moderate contact frequency (3-5 contacts) maximizes results, while excessive contacts reduce effectiveness. Ensuring data quality by handling missing or inconsistent values is critical for accurate analysis and improved campaign outcomes
