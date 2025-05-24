# Marketing-Dashboard-Mock-PowerBI

## Screenshot of the dashboard
![test_marketing_campaign_dashboard](https://github.com/user-attachments/assets/70d6c98f-f258-4339-937d-38665f9e3515)

## Demo
![PBIDesktop_m2XnLlj9UD](https://github.com/user-attachments/assets/aa43c687-8008-48a9-83bc-8dffbcc8a1a9)

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
Some questions I came up with while looking at the raw data:

1. How many of the client's emails were clicked, opened and downloaded?
2. What is the location breakdown of the marketing campaing?
3. Which industries and companies engaged most with the campaign?
4. What is the average revenue of industries and companies that engage with the marketing campaigns?
5. What is the breakdown of the client's emails by seniority?
6. What is the breakdown of the client's emails by industry?
7. What is the breakdown of the marketing campaign by function?
8. Which of the marketing assets performed the best?

## Summary of Findings
1. There were 988 opens by 156 companies, 64 clicks by 45 companies, and 7 downloads by 7 companies.
2. The companies all are located in varying regions across the United States. Engagements were mostly concentrated in urban states such as New York, Massachussetts, Michigan and California, with others from Texas, Florida and Colorado.
3. The marketing campaign were reached mostly by 156 companies across Hospitals & Physicians Clinics, Insurance, Manufacturing, Medical Devices & Equipment, Pharmaceuticals, followed by other industries. From the treemap, the most engaged companies in the Hospital industry Ascension, Avera Health, Kaiser, AdventHealth, and Norwell are the top companies. In Insurance, the top two are UnitedHealth Group and MetLife.
4. Based on the scatter plot, the industry with the highest revenue is the Insurance industry which generates close to $100 B, followed by Medical Devices and Manufacturing with around $60 B and $30 B respectively. As mentioned, most of the engagement stems from the Hospitals industry which generates around $10 B annually.
5. Around 60% are Directors who engaged with the marketing campaign, followed by C-Levels and VPs at 24% and 15% respectively, followed by the rest.
6. Most were from the Hospitals industry (546 engagements), followed by Insurance (210 engagements), Manufacturing (168 engagements), Pharmacies (71 engagements), and Medical Devices (31 engagements).
7. Most of the engagements were from people in the IT and Compliance functions (33% and 30% respectively), followed by Risk (14%), Medical Administration (12%) and Operations (10%).
8. EB01 performed the best as it has the highest number of engagements at 483, followed by EB02 (307 engagements), EB03 (210 engagements) and CYG (59 engagements).

## Recommendations
- Focus on increasing the engagement of industries that generate the highest annual revenue, which are the Insurance, Medical Devices and Manufacturing Industries. They should also continue to prioritize and tailor campaigns for Hospitals & Physician Clinics and consider expanding campaigns with tailored messaging.
- Campaigns EB01 and EB02 performed the best. Investigate what made these campaigns perform and develop custom content and refine their targeting.
- In general, the East Coast (New York, Toronto, Chicago) and West Coast (California) show concentrated engagements. Client A should double down on digital ad spend and outreach in these regions.
- Tailor email campaigns specifically to address painpoints by the top engaging functions, such as IT, Compliance and Risk.
- Consider personalized outreach to senior leadership and decision-makers. Currently, Directors are most engaged, whereas C-levels is relatively under-engaged.
- Companies like Ascension, UnitedHealth Group, and Colgate-Palmolive are most engaged. Consider offering tailored follow-ups, case studies or direct meetings for conversion.
- Analyze industries which show relatively low engagement, which are Healthcare, Chemicals, Pharmaceuticals, Medical Devices and Manufacturing. Investigate where content is too generic and/or not addressing key concerns in these sectors.
- From the engagement filters, most seem to be "Opened" rather than deeper engagement like "Clicked" or "Downloaded". Optimize CTA placement, content quality and follow-up strategy to drive deeper interactions beyond email open.
