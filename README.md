# Marketing-Dashboard-Mock-PowerBI

![test_marketing_campaign_dashboard](https://github.com/user-attachments/assets/70d6c98f-f258-4339-937d-38665f9e3515)


## Data Used

**Data** - Mock data for a marketing campaign conducted by Client A.

**Data Cleaning & Analysis** - PowerQuery

**Data Visualization** - PowerBI

## Background & Purpose
Client A requested a dashboard to analyze the performance of an email campaign they recently ran. They have provided a sheet of data to reference, but only provided engagements that occurred after the email was delivered. Ensure the dashboard includes all relevant performance metrics and other fields that would help them understand their audience better.

## Description of the Data
A cursory glance at the sheet shows the personal and company information of each person who interacted with Client A's marketing campaign. The data is complete, with no missing/invalid values. There are 1,059 rows, 12 categorical columns and 2 numerical columns. The columns are self-explanatory, however it is unclear what the four different values in the ```_asset``` column denotes, possibly each marketing campaign that was run. The data is a snapshot of the client's campaign metrics at a single point in time, thus there is no longitudinal analysis in this case study.

| **Column**  | **Type** |
| -------- | ------- |
| _email | Text    |
| _name | Text     |
| _seniority | Text    |
| _function | Text |
| _state | Text |
| _country | Text |
| _classification | Text |
| _industry | Text |
| _annualRevenue | Integer |
| _employeeCount | Integer |
| _asset | Text |
| _engagement | Text |

## Methodology
A few minor transformations were perfomed on the data in the spreadsheet, including the use of a PivotTable to understand the count of ```_engagement``` by each type and PowerQuery to perform minor cleaning before loading into PowerBI.

## Questions
A few questions key questions I came up with while looking at the raw data:

1. How many of the client's emails were clicked, opened and downloaded?
2. What is the location breakdown of the marketing campaing?
3. Which industries and companies engaged most with the campaign?
4. What is the average revenue of industries and companies that engage with the marketing campaigns?
5. What is the breakdown of the client's emails by seniority?
6. What is the breakdown of the client's emails by industry?
7. What is the breakdown of the marketing campaign by function?
8. Which of the marketing assets performed the best?

## Summary of Findings
1. sdfvf
2. The companies all are located in varying regions across the United States. Engagements were mostly concentrated in urban states such as New York, Massachussetts, Michigan and California, with others from Texas, Florida and Colorado.
3. The marketing campaign were reached mostly by 156 companies across Hospitals & Physicians Clinics, Insurance, Manufacturing, Medical Devices & Equipment, Pharmaceuticals, followed by other industries. From the treemap, the most engaged companies in the Hospital industry Ascension, Avera Health, Kaiser, AdventHealth, and Norwell are the top companies. In Insurance, the top two are UnitedHealth Group and MetLife.
4. Based on the scatter plot, the industry with the highest revenue is the Insurance industry which generates close to $100 B, followed by Medical Devices and Manufacturing with around $60 B and $30 B respectively. As mentioned, most of the engagement stems from the Hospitals industry which generates around $10 B annually.
5. Around 60% are Directors who engaged with the marketing campaign, followed by C-Levels and VPs at 24% and 15% respectively, followed by the rest.
6. 

