\## Business Problem Statement



The company launched a new onboarding and activation campaign to improve user conversion and early engagement. Users were divided into a Control group (existing onboarding experience) and a Treatment group (new onboarding experience).



The key business decision is whether the new onboarding experience should be rolled out to all users.



This decision impacts product teams, marketing teams, leadership, and future users of the platform.



The primary objective is to improve user conversion to paid subscriptions while maintaining a positive user experience.



Potential risks include increased refunds, higher support ticket volume, lower engagement, or slower conversions.



Before making a recommendation, evidence is required showing that the Treatment group performs better than the Control group on key business metrics and that guardrail metrics do not indicate significant risk.



\---



\## North Star Metric



The North Star Metric selected for this experiment is Paid Conversion Rate.



Paid Conversion Rate measures the percentage of users who convert from free users to paying subscribers. This metric is the most important success indicator because the company operates a subscription-based business model and revenue growth depends on increasing the number of paying customers.



Other metrics such as landing page visits, trial starts, onboarding completion, engagement score, and revenue are important supporting metrics because they help explain why conversion changes, but they do not directly represent the final business outcome.



Optimizing only Paid Conversion Rate without monitoring guardrail metrics could create problems such as increased refunds, poor customer experience, lower engagement quality, or increased support burden.



\---



\## KPI Tree Summary



The KPI tree for this experiment uses Paid Conversion Rate as the North Star Metric.



Primary drivers include:

\- Trial Activation

\- Onboarding Success

\- User Engagement



Guardrail metrics include:

\- Refund Rate

\- Support Ticket Rate

\- Revenue Quality



The KPI tree image is included in the outputs folder and a preview screenshot is included in the screenshots folder.



\---



\## Data Quality Checks



The experiment dataset was reviewed before analysis.



Checks performed:

\- Missing values

\- Duplicate user IDs

\- Group count verification

\- Binary value validation

\- Revenue outlier review

\- Region distribution across groups

\- Device type distribution across groups

\- Traffic source distribution across groups



Detailed findings are documented in the analysis workbook.



\---



\## Dataset Description



The dataset contains user-level experiment data from a subscription-based digital product company. Users were randomly assigned to either a Control group (existing onboarding experience) or a Treatment group (new onboarding experience).



The dataset includes user demographics, experiment group assignment, onboarding activity, conversion outcomes, revenue metrics, engagement scores, refund requests, support ticket activity, and conversion timing information.



\---



\## Experiment Analysis Approach



The analysis followed a structured experiment evaluation process.



Steps included:



\* Data quality validation

\* Duplicate user review

\* Missing value checks

\* Segment distribution checks

\* KPI comparison between Control and Treatment groups

\* Calculation of conversion, revenue, engagement, and support metrics

\* Statistical hypothesis testing

\* Guardrail metric evaluation

\* Business recommendation development



The primary metric used for decision-making was Paid Conversion Rate.



\---



\## Hypothesis Test Summary



A Two-Proportion Z-Test was performed using Paid Conversion Rate as the primary metric.



Results:



\* Control Conversion Rate = 3.17%

\* Treatment Conversion Rate = 6.99%

\* One-Tailed P-Value = 0.000573



Since the p-value was below the significance level of 0.05, the null hypothesis was rejected.



The analysis provides statistically significant evidence that the Treatment experience improved conversion performance.



\---



\## Guardrail Metrics Considered



The following guardrail metrics were evaluated:



\* Refund Rate

\* Support Ticket Rate

\* Engagement Score

\* Average Days To Convert

\* Revenue Per Converted User



While conversion performance improved, increases in support ticket volume and reductions in revenue per converted user were identified as potential business risks.



\---



\## Final Recommendation



Recommendation: Continue Testing



The Treatment experience significantly improved Paid Conversion Rate and multiple supporting metrics. However, support ticket volume increased substantially and revenue per converted user declined.



Additional investigation is recommended before a full rollout to all users.



\---



\## Assumptions:



\* Experiment group assignment was random.

\* Conversion tracking was accurate.

\* Revenue data was recorded correctly.



\## Limitations:



\* Duplicate user records were identified.

\* Missing values were present in some fields.

\* The experiment reflects a limited observation period.

\* Long-term customer value was not evaluated.



\---



\## Screenshots Included



The repository includes the following screenshots:



\* summary\_metrics.png

\* hypothesis\_test\_output.png

\* kpi\_tree\_preview.png



These screenshots provide evidence of KPI calculations, statistical testing, and KPI framework design.

