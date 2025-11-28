# Smartway Payments Metrics Dashboard
 
**Author:** Odongo Babra 
**Date:** 2025-11-28

--- 
 
## Project Background 
This project analyzes Smartway Bank’s transaction data to tackle challenges like failed transactions, ineffective fraud blocking, and network performance issues. An interactive Excel dashboard highlights insights and offers practical solutions to improve transaction approvals, optimize network resources, and guide app development priorities.

--- 
 
## Project Objective 
- Assess real-time fraud detection and blocking, measuring effectiveness and any latency between flagging and prevention.
- Evaluate the performance of Network Slice 1 and 2 compared to baseline networks on key metrics (latency, success rate, throughput) and analyze cost versus benefit
- Recommend which platform Mobile or Desktop should be prioritized for fixes, specifying the most critical features and user flows.
- Identify whether transaction rejections are due to banking errors or network issues, supported by evidence and confidence levels.

--- 
 
## Datasets 

**Patients.csv ** -  transaction id, sender account id, receiver account id, transaction amount, transaction type, date, time, hour, timestamp, transaction status, fraud flag, pin code, network slice id, slice bandwidth (mbps), latency (ms), device used, geolocation(latitude, and longitude).

--- 
## Dashboard Features 
-	Key KPIs: total number of transactions, average transaction amount, total succesful transactions  
-	Visuals include column charts, clustered column charts, stacked column charts, and bar charts to represent hourly and time-range transaction trends, success vs failed transactions, average latency, average slice bandwidth, network slice performance comparisons, and device/platform usage.
-	Interactivity: slicers for Transaction Type, Transaction Status, Month and Time Range
--- 
## Key Findings
1.	In network slice performance, Slice 2 records the most successful transactions, while Slice 1 has the highest number of failures. 
2.	Transactions by hour show that early morning (0–5) has the highest number of both successes and failures, while late night (21–23) has the lowest.
3.	Desktops have the highest number of transactions and also the most successful ones.
4.	The transactions that were falsely flagged show a higher number of failed transactions
5.	The number of successful transactions is generally higher than failed transactions.

--- 
## Recommendations 
1.	Improve the performance of the app and mobile site, since desktops perform best, by optimizing speed, fixing bugs, and ensuring smooth transaction flow across all devices.
2.	Schedule all system maintenance and updates during early morning hours to minimize user disruption..
3.	Reassess Slice 1 configuration and usage to reduce failures, and monitor Slice 2 to ensure it continues delivering high success rates. Consider reallocating traffic or upgrading infrastructure based on performance data.
4.	Review and adjust fraud system rules to reduce false positives so that valid transactions are not blocked, while still keeping security strong.

 
--- 
 
## Tools & Techniques 
-	Microsoft Excel (Pivot Tables, Pivot Charts, Slicers)   
-	Data cleaning and transformation in Excel   
-	Dashboard layout and visualization best practices   
-	Basic descriptive analytics and KPI design 
 
--- 
 
## Project Files (included) 
-	`Smartway Metrics Dashboard.xlsx` — interactive dashboard file   
-	`Transaction datasets` — raw data files used for analysis (CSV / XLSX)   
-	`Smartway Presentation.pdf` — boardroom slide deck (14 slides)   
-	`README.md` — this documentation 
-	`MP_Excel_Project_2` – The problem
 
--- 
 
## How to Run / View 
1.	Open `Dashboard.xlsx` in Excel (desktop recommended)   
2.	Enable content (if prompted) to allow Pivot Tables and slicers to work   
3.	Use slicers to filter for Age group, Day of the week , Medication type.   
4.	Refer to `Presentation.pdf` for a summary of insights and recommended actions 
 
 

 
--- 
 
## Contact 
Babra Odongo
odongobabra5@gmail.com
https://www.linkedin.com/in/babra-odongo-047921268/


