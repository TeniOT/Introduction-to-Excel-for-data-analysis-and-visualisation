# Bike Sales Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)
- [References](#references)



### Project Overview
---
This data analysis project aims to provide insights into the sales performance of a Bicycle company in the year 2021. By analysing various aspects of the sales data, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding of the company's performance.


![Sales Summary](https://github.com/TeniOT/Excel-visual/assets/164643376/5346f317-04a4-49b5-abf5-df3d79f4a07c)



### Data Sources 
Sales Data: The primary dataset used for this analysis is the "bike sales.csv" file, containing detailed information about each sale made by the company.



### Tools
- Microsoft 365 (Office) Excel
  - [Download Here](https://skillsforall.com/launch?id=1b81c11b-147b-49aa-8f87-a3469f24d280&tab=curriculum&view=98cbced0-abf6-53ca-b984-ef587df3e600)



### Data Cleaning
In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection
   - The Extract, Transform and Load (ETL) process.
2. Data cleaning and formatting.
   - Fixing and Removing Duplicates.
   - Handling missing values.
   - Conditional Formatting.
   - Data Parsing from Text to Column.
   ```Excel
     =TRIM()
     =LEN()
   ``` 



### Exploratory Data Analysis
EDA involved exploring the sales data to answer key questions, such as:
- What is the Average Cost?
- What is the Average Revenue?
- Determine the purchasing patterns of different demographic groups to identify areas to concentrate marketing efforts




### Data Analysis
```Excel
=AVERAGE()
=MAX()
=MIN()
=SUM()
=VLOOKUP()
=XLOOKUP()
=IF(ISNA(VLOOKUP()),"Unique","Duplicate")
```
- Pivot Table to Select Data for Analysis
- Addressing Anomalies in data
  - Use a Scatter Chart to Find Outliers
![Outliers](https://github.com/TeniOT/Introduction-to-Excel-for-data-analysis-and-visualisation/assets/164643376/8ec4d0af-a901-45f4-b4dd-7f91d8b0363f)

```Excel
  =LARGE()
  =SMALL()
```



### Results and Findings
The analysis results are summarised as follows:
- Average Cost = £26,479
- Average Revenue = £43,764
- The youth age group is globally the poorest area of sales.
- Female adults are buying the most product and should be targeted for marketing efforts.




### Recommendations
Based on the analysis, we recommend the following actions: the company can develop business decisions in relation to:
- Invest in marketing and promotions in youth age group globally.
- Focus on promoting sales in Australia for the male youth and in France for adult males.
- Implement a customer segmentation strategy to target Female adults effectively.
- Implement strategies to develop business decisions for sales in the United Kingdom as it has only one successful market category, that is, Youth.




#### References
1. Microsoft 365 OneDrive
2. [Cisco Skills for All](https://skillsforall.com/)
3. [Her Data Project](https://www.youtube.com/watch?v=0N9xekdKCwk)
