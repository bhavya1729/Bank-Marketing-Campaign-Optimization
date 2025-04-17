# Bank-Marketing-Performance-Analysis: Data-Driven Insights to Optimize Term Deposit Conversions
🎯 Project Goal
The goal of this project is to investigate the performance of a bank’s term deposit marketing campaigns in order to surface actionable recommendations for resource allocation and improved conversion rates. The analysis focuses on four key areas:

Customer segmentation (identifying high- and low-converting groups)

Temporal patterns (seasonal and day-of-week trends)

Economic drivers (e.g., interest rates, employment volatility)

Model performance (predictive accuracy and practical limitations)

🗂️ Dataset Structure
The dataset consisted of client and campaign-level data, including:

Client Demographics: Age, job type, marital status, education level

Campaign Details: Contact method, call duration, previous campaign outcomes

Economic Indicators: Euribor 3-month interest rates, employment variation rates, consumer confidence

Target Variable: Whether the client subscribed to a term deposit (yes/no)

📌 Insights Summary
1️⃣ Overall Conversion Patterns
High Retention, Poor Acquisition:

Past successful clients had a 65% conversion rate but comprised only 3% of the dataset

New leads and failed contacts had rejection rates of 91% and 86%, dragging the overall rate to 11%

🔧 Recommendation:
Retain loyal clients while refining new lead targeting with predictive modeling or segmentation.

2️⃣ Occupation-Based Conversion Rates
Top Performers:

Students: 31.4%

Retirees: 25.2%

Underperformers:

Blue-Collar: 6.9%

Service Workers: 8.1%

Management: 11.2%

Technicians: 10.8%

🔧 Recommendations:

Prioritize students and retirees with tailored content

Redesign messaging for professionals to address concerns

Deprioritize blue-collar and service groups

3️⃣ Age-Based Conversion Trends
U-shaped pattern observed:

Under 30: 15.2%

Over 50: 15.1%

30–50 years: 9.1%

🔧 Recommendations:

Maintain strong campaigns for youth and seniors

Introduce flexible offerings for the mid-career group (30–50)

4️⃣ Day-of-Week Performance
Best Days:

Thursday: 12.1%

Tuesday & Wednesday: ~11.6–11.8%

Worst Day:

Monday: 9.9%

🔧 Recommendations:

Allocate 25–30% of weekly calls to Thursdays

Reduce Monday call volume

5️⃣ Seasonal Trends
High-Performance Months:

March: 50.5%

September to December: 45–49%

Low-Performance Months:

May to July: <10%

🔧 Recommendations:

Focus 60–70% of outreach in March and Q4

Reduce campaigns during summer

6️⃣ Economic Factors
Negative Correlations:

Euribor3m: -0.31

Employment volatility: -0.30

Minimal Impact:

Consumer confidence: +0.05

🔧 Recommendations:

Monitor interest rates and employment data

Align messaging with macroeconomic trends

7️⃣ Call Duration Insights
30+ minute calls: 59.4% conversion, but rare (101 instances)

5–10 minute calls: 23% conversion, more common

🔧 Recommendations:

Train reps to maximize impact in 5–10 minute calls

Improve scripts and efficiency

8️⃣ Loan Status & Conversion
Highest: Housing loan only – 11.7%

Lowest: Personal loan only – 10.7%

🔧 Recommendations:

Focus on clients with housing loans

Deprioritize those with personal loans due to possible liquidity issues

🤖 Model Performance
Precision for Non-Subscribers: 94% – effective at reducing wasted calls

Precision for Subscribers: 37% – many false positives

Best Model: Random Forest (AUC 0.790)

🔧 Recommendations:

Use Random Forest for campaign filtering

Further refine to reduce false positives

✅ Final Recommendations
📌 Resource Allocation
Focus on students, retirees, and past successful clients

Deprioritize blue-collar/service segments and May–July efforts

🗓️ Campaign Timing
Schedule 25–30% of calls on Thursdays

Concentrate annual efforts in Q4 (Sept–Dec)

Experiment with motivational offers on Mondays

💡 Product Design
Develop flexible products for the 30–50 age group

Link promotions to falling Euribor rates
