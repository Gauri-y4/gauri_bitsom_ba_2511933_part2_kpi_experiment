\# Hypothesis Test



\## Primary Metric



Paid Conversion Rate



\## Business Objective



Determine whether the Treatment experience increases the percentage of users who convert into paying customers compared to the Control experience.



\## Null Hypothesis (H0)



There is no difference in paid conversion rate between the Treatment group and the Control group.



H0: p\_treatment = p\_control



\## Alternative Hypothesis (H1)



The Treatment group has a higher paid conversion rate than the Control group.



H1: p\_treatment > p\_control



\## Test Type



One-tailed test



\## Significance Level



α = 0.05



\## Reason for Choosing the Metric



Paid conversion rate directly impacts revenue and business growth. Increasing the percentage of users who become paying customers is the primary goal of the experiment.



\## Decision Rule



If p-value < 0.05:



Reject the null hypothesis and conclude that the Treatment significantly improves paid conversion rate.



If p-value ≥ 0.05:



Fail to reject the null hypothesis.



\## Interpretation Logic



A statistically significant increase in paid conversion rate indicates that the Treatment experience is more effective at converting users into paying customers and may be considered for rollout.



\---



\## Hypothesis Test Result



\### Test Used



Two-Proportion Z-Test



\### Test Inputs



Control Group



\* Sample Size = 693

\* Paid Conversions = 22

\* Conversion Rate = 3.17%



Treatment Group



\* Sample Size = 715

\* Paid Conversions = 50

\* Conversion Rate = 6.99%



\### Test Output



\* Z Score = -3.2519

\* One-Tailed P-Value = 0.000573



\### Decision Rule



If p-value < 0.05, reject the null hypothesis.



If p-value ≥ 0.05, fail to reject the null hypothesis.



\### Decision



Since 0.000573 < 0.05, the null hypothesis is rejected.



\### Business Interpretation



The Treatment group achieved a statistically significant improvement in paid conversion rate compared to the Control group.



The increase from 3.17% to 6.99% is unlikely to have occurred by random chance.



The experiment provides strong evidence that the Treatment experience improves user conversion into paying customers.



\---



\## **Guardrail Metric Evaluation**



\### Refund Rate



Control: 0.00%

Treatment: 0.42%



Refund rate increased slightly in the Treatment group. This may indicate a small increase in customer dissatisfaction after purchase. However, the overall refund rate remains low.



\### Support Ticket Rate



Control: 21.93%

Treatment: 37.20%



Support ticket rate increased substantially in the Treatment group. This suggests users may require more assistance, which could increase operational costs and place additional pressure on support teams.



\### Engagement Score



Control: 57.03

Treatment: 62.93



Engagement score improved in the Treatment group, indicating that users interacted more actively with the product.



\### Days To Convert



Control: 8.86 days

Treatment: 6.40 days



Users converted faster in the Treatment group. Faster conversion is beneficial because revenue is realized sooner.



\### Revenue Per Converted User



Control: 1630.10

Treatment: 770.41



Revenue per converted user decreased significantly in the Treatment group. Although more users converted, each converted customer generated less revenue, which may affect profitability.



\### Overall Guardrail Assessment



The Treatment improved engagement and reduced conversion time. However, support ticket rate increased significantly and revenue per converted user decreased substantially. These factors create business risk and should be considered before a full rollout.





