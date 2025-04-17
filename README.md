# Bank-Marketing-Performance-Analysis: Data-Driven Insights to Optimize Term Deposit Conversions
Project Goal
The goal of this project is to investigate the performance of a bank’s term deposit marketing campaigns in order to surface actionable recommendations for resource allocation and improved conversion rates. The analysis focuses on four key areas:

Customer segmentation (identifying high- and low-converting groups)

Temporal patterns (seasonal and day-of-week trends)

Economic drivers (e.g., interest rates, employment volatility)

Model performance (predictive accuracy and practical limitations)

Insights Summary
Overall Conversion Patterns

High Retention, Poor Acquisition: Past successful clients converted at a high rate (65%), but this group only comprises 3% of the audience. Meanwhile, new leads and previously failed contacts had high rejection rates of 91% and 86%, dragging the overall conversion rate down to 11%.

Recommendation: Retain and nurture existing loyal clients while refining the targeting strategy for new prospects using predictive modeling or segmentation.

Occupation-Based Conversion Rates

Students (31.4%) and Retirees (25.2%) showed significantly above-average conversion, suggesting strong alignment with term deposit goals like savings and retirement planning.

Recommendation: Prioritize outreach to Students and Retirees by tailoring content and allocating more resources toward these high-converting groups.

Management (11.2%) and Technicians (10.8%) underperformed despite likely income stability.

Recommendation: Redesign messaging for these groups, perhaps by addressing risk concerns, liquidity, or long-term benefits.

Blue-Collar (6.9%) and Services (8.1%) segments had the lowest conversions.

Recommendation: Consider reducing marketing investment in these groups due to consistently poor returns.

Age-Based Conversion Trends

A U-shaped pattern was observed: clients under 30 and over 50 had strong conversion rates (~15.2% and ~15.1%, respectively), likely driven by savings and retirement goals. In contrast, the 30–50 age group underperformed at 9.1%.

Recommendation: Maintain strong campaigns for youth and seniors. Introduce flexible or hybrid offerings for the 30–50 age group to address financial pressures.

Day-of-Week Performance

Thursday (12.1%), Tuesday (11.8%), and Wednesday (11.6%) had the highest conversion rates.

Recommendation: Allocate 25–30% of weekly calls to Thursdays and schedule follow-ups mid-week. Reduce outreach volume on Mondays (9.9%), which showed lower performance.

Seasonal Trends

March had an exceptional 50.5% conversion rate, with September to December also maintaining strong performance, likely due to year-end financial planning.

May and July had the weakest results (below 10%), likely due to summer holidays.

Recommendation: Concentrate 60–70% of annual outreach during high-performing months (March and Sept–Dec). Reduce investment during low-conversion months.

Economic Factors

Employment volatility correlated with lower conversion due to economic uncertainty.

Higher Euribor3m interest rates negatively impacted subscriptions.

Consumer confidence had minimal impact.

Recommendation: Monitor macroeconomic indicators closely to adapt campaign timing and messaging to market conditions.

Call Duration Insights

30+ minute calls converted at 59.4%, but occurred rarely (only 101 instances).

5–10 minute calls showed realistic success at 23%.

Recommendation: Focus on improving 5–10 minute calls through better scripts and rep training for efficiency and impact.

Loan Status & Conversion

Highest conversion (11.7%): Clients with housing loans only.

Lowest conversion (10.7%): Clients with personal loans only.

Recommendation: Target clients with housing loans more aggressively and deprioritize those with only personal loans, possibly due to liquidity constraints.

Model Performance

The model showed 94% precision in filtering non-subscribers, indicating efficient reduction of wasted outreach.

However, it only had 37% precision in predicting actual subscribers, leading to a high false positive rate.

Recommendation: Use the Random Forest model, which had slightly higher precision, and continue refining it to better identify true positives.

Recommendations
Focus on Retention: Build loyalty programs or personalized offers for the small but highly converting base of previous successful clients.

Double Down on High-Performers: Increase budget for Students and Retirees, and schedule major outreach on Thursdays and during March and Q4.

Refine Midlife Strategy: Develop custom offers for 30–50-year-olds to boost performance in this large but underperforming segment.

Optimize Operations: Streamline calls to the 5–10 minute range with better training and scripting.

Adjust for Seasonality: Scale back efforts in low-performing months like May and July.

Improve Targeting Models: Enhance machine learning models to reduce false positives and improve subscriber prediction.
