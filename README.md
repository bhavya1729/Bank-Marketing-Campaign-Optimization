# Bank-Marketing-Performance-Analysis: Data-Driven Insights to Optimize Term Deposit Conversions
**Project Goal**

The goal of this project is to investigate the performance of a bank’s term deposit marketing campaigns in order to surface actionable recommendations for resource allocation and improved conversion rates. The analysis focuses on four key areas:

-Customer segmentation (identifying high- and low-converting groups)
-Temporal patterns (seasonal and day-of-week trends)
-Economic drivers (interest rates, employment volatility)
-Model performance (predictive accuracy and practical limitations)

_Dataset Structure_
The dataset consisted of client and campaign-level data, including:
Client Demographics: Age, job type, marital status, education level
Campaign Details: Contact method, call duration, previous campaign outcomes
Economic Indicators: Euribor 3-month interest rates, employment variation rates, consumer confidence
Target Variable: Whether the client subscribed to a term deposit (yes/no)

_Insights Summary_

1. Overall Conversion Patterns
High Retention, Poor Acquisition:
Past successful clients had a 65% conversion rate but comprised only 3% of the dataset
New leads and failed contacts had rejection rates of 91% and 86%, dragging the overall rate to 11%
Recommendation:
Retain loyal clients while refining new lead targeting with predictive modeling or segmentation.

2. Occupation-Based Conversion Rates
-Top Performers:
Students: 31.4%
Retirees: 25.2%
-Underperformers:
Blue-Collar: 6.9%
Service Workers: 8.1%
Management: 11.2%
Technicians: 10.8%
Recommendations:
Prioritize students and retirees with tailored content
Redesign messaging for these groups, perhaps by addressing risk concerns, liquidity, or long-term benefits.
Deprioritize blue-collar and service groups

3. Age-Based Conversion Trends
U-shaped pattern was observed: clients under 30 and over 50 had strong conversion rates (~15.2% and ~15.1%, respectively), likely driven by savings and retirement goals.
In contrast, the 30–50 age group underperformed at 9.1%.
Recommendation:
Maintain strong campaigns for youth and seniors. Introduce flexible or hybrid offerings for the 30–50 age group to address financial pressures.

4. Day-of-Week Performance
Thursday (12.1%), Tuesday (11.8%), and Wednesday (11.6%) had the highest conversion rates.
Recommendation:
Allocate 25–30% of weekly calls to Thursdays and schedule follow-ups mid-week. Reduce outreach volume on Mondays (9.9%), which showed lower performance.

5. Seasonal Trends
March had an exceptional 50.5% conversion rate, with September to December also maintaining strong performance, likely due to year-end financial planning.
May and July had the weakest results (below 10%), likely due to summer holidays.
Recommendation:
Concentrate 60–70% of annual outreach during high-performing months (March and Sept–Dec). Reduce investment during low-conversion months.

6. Economic Factors
Employment volatility correlated with lower conversion due to economic uncertainty.
Higher Euribor3m interest rates negatively impacted subscriptions.
Consumer confidence had minimal impact.
Recommendation:
Monitor macroeconomic indicators closely to adapt campaign timing and messaging to market conditions.



7. Call Duration Insights
30+ minute calls: 59.4% conversion, but rare (101 instances)
5–10 minute calls: 23% conversion, more common
Recommendation:
Focus on improving 5–10 minute calls through better scripts and rep training for efficiency and impact.


8. Loan Status & Conversion
Highest: Housing loan only – 11.7%
Lowest: Personal loan only – 10.7%
Recommendation: 
Target clients with housing loans more aggressively and deprioritize those with only personal loans, possibly due to liquidity constraints.



_Model Performance_

The model showed 94% precision in filtering non-subscribers, indicating efficient reduction of wasted outreach.
However, it only had 37% precision in predicting actual subscribers, leading to a high false positive rate.
Recommendation: 
Use the Random Forest model(AUC 0.790), which had slightly higher precision, and continue refining it to better identify true positives.



_Final Recommendations_


- Resource Allocation


Build loyalty programs or personalized offers for the small but highly converting base of previous successful clients.

Focus on students, retirees, and past successful clients

Deprioritize blue-collar/service segments and May–July efforts

- Campaign Timing

schedule major outreach on Thursdays and during March and Q4 (september- december).

- Product Design
 
 Develop custom offers for 30–50-year-olds to boost performance in this large but underperforming segment.

Link promotions to falling Euribor rates
