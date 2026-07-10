## Question 1 - Customer Churn Distribution

## Business Question

How many customers have churned, and what is their proportion compared to the total customer base?

## Findings

- Total Customers: 4,250
- Churned Customers: 598
- Non-Churned Customers: 3,652
- Churn Rate: 14.07%

## Business Insight

Out of 4,250 customers, 598 customers discontinued the service, resulting in a churn rate of 14.07%. Approximately one out of every seven customers left the company. This establishes the baseline churn rate and highlights the importance of customer retention.


## Question 2 - Account Length vs Churn

### Findings

- Average Account Length (Non-Churned): 99.92 months
- Average Account Length (Churned): 102.14 months

### Business Insight

Customers who churned had a slightly higher average account length (approximately 2.2 months more) than non-churned customers. This difference is relatively small, suggesting that account tenure alone is unlikely to be a major factor influencing customer churn.


## Question 3 - International Plan vs Churn

### Findings

- Churn Rate (International Plan = Yes): 42.17%
- Churn Rate (International Plan = No): 11.18%

### Business Insight

Customers with an International Plan exhibit a substantially higher churn rate than customers without the plan. While this does not establish causation, it identifies the International Plan segment as a high-risk customer group that warrants further investigation.


## Question 4 - Customer Service Calls vs Churn

### Findings

- Average Customer Service Calls (Non-Churned): 1.44
- Average Customer Service Calls (Churned): 2.28

### Business Insight

Customers who churned contacted customer service more frequently than those who remained. This pattern suggests that service-related issues or customer dissatisfaction may be associated with churn and should be investigated further.


## Question 5 - Call Charges vs Churn

### Findings

| Charge Type | Non-Churned | Churned |
|--------------|------------:|--------:|
| Day Charge | 29.84 | 35.53 |
| Evening Charge | 16.88 | 17.85 |
| Night Charge | 8.98 | 9.29 |

### Business Insight

Customers who churned consistently incurred higher average call charges across all periods. The greatest difference was observed in daytime call charges, indicating that higher daytime calling expenses may be more closely associated with customer churn than evening or night charges.


## Question 6 - Total Day Minutes vs Churn

### Findings

- Average Day Minutes (Non-Churned): 175.56
- Average Day Minutes (Churned): 208.99
- Difference: 33.43 minutes

### Business Insight

Customers who churned spent significantly more time on daytime calls than customers who remained. This finding is consistent with the higher average daytime charges observed in Question 5, suggesting that heavy daytime usage may be associated with increased churn risk.


## Question 7 - Total Evening Minutes vs Churn

### Findings

- Average Evening Minutes (Non-Churned): 198.57
- Average Evening Minutes (Churned): 209.96
- Difference: 11.39 minutes

### Business Insight

Customers who churned averaged **209.96 evening call minutes**, while non-churned customers averaged **198.57 minutes**. The difference of **11.39 minutes** is relatively small, indicating that evening call usage has a weaker association with customer churn compared to daytime call usage.


## Question 8 - International Usage and Charges vs Churn

### Findings

- Average International Minutes (Non-Churned): 10.19
- Average International Minutes (Churned): 10.63
- Average International Charges (Non-Churned): 2.75
- Average International Charges (Churned): 2.87

### Business Insight

Customers who churned showed only slightly higher international usage and charges than non-churned customers. While the differences were minimal, this finding complements Question 3 by suggesting that subscription to the International Plan has a stronger association with churn than the actual level of international usage.


## Question 9 - Total Day Calls vs Churn

### Findings

- Average Day Calls (Non-Churned): 99.81
- Average Day Calls (Churned): 100.48
- Difference: 0.67 calls

### Business Insight

The average number of daytime calls is nearly the same for churned and non-churned customers. This contrasts with the much larger difference observed in total daytime minutes, indicating that the length of calls is more strongly associated with churn than the number of calls made.


## Question 10 - Average Evening Charges vs Churn

### Findings

- Average Evening Charges (Non-Churned): 16.88
- Average Evening Charges (Churned): 17.85
- Difference: 0.97

### Business Insight

Churned customers incurred only slightly higher evening call charges than non-churned customers. Compared to the larger differences observed in daytime usage and charges, evening charges appear to have a weaker association with customer churn.

# Executive Summary - Basic Analysis

The analysis of the first ten business questions reveals several important patterns related to customer churn:

- The overall churn rate is 14.07%, establishing the baseline level of customer attrition.
- Customers subscribed to the International Plan exhibit a substantially higher churn rate (42.17%) than customers without the plan (11.18%), making it the strongest churn indicator identified in the basic analysis.
- Churned customers make more customer service calls on average, suggesting that service-related issues may contribute to customer dissatisfaction.
- Daytime calling behavior is more strongly associated with churn than evening or international usage. Churned customers spend significantly more time on daytime calls and incur noticeably higher daytime call charges.
- Evening usage and charges show only modest differences between churned and non-churned customers.
- International usage and charges differ only slightly, indicating that the presence of an International Plan is a stronger indicator of churn than the amount of international usage itself.
- The number of daytime calls is nearly identical between the two groups, suggesting that call duration is a more meaningful indicator than call frequency.

Overall, the strongest indicators of churn identified in the basic analysis are International Plan subscription, higher daytime usage, higher daytime charges, and increased customer service interactions.



# Medium Question 1 - Churn Rate by Area Code

## Business Question

Perform a segmented analysis of churn by area code. Is there a particular area with a significantly higher churn rate?

## Findings

| Area Code | Total Customers | Churned Customers | Churn Rate |
|-----------|----------------:|------------------:|-----------:|
| 408 | 1086 | 152 | 14.00% |
| 415 | 2108 | 287 | 13.61% |
| 510 | 1056 | 159 | 15.06% |

## Key Observation

- Area Code **510** has the highest churn rate (**15.06%**).
- Area Code **415** has the lowest churn rate (**13.61%**).
- The difference between the highest and lowest churn rates is only **1.45 percentage points**.

## Business Insight

Although Area Code **510** records the highest churn rate, the variation across all three area codes is relatively small. This indicates that **geographic location alone is not a strong predictor of customer churn**. Customer behavior, service usage patterns, and subscription plans are likely to have a greater influence on churn than the customer's area code.

## Recommendation

Area Code **510** can be monitored slightly more closely because it has the highest churn rate. However, retention strategies should focus primarily on stronger churn indicators identified in the Basic Analysis, such as:

- International Plan subscription
- Higher daytime call usage
- Higher daytime call charges
- Increased customer service calls

These factors are likely to provide a greater impact on churn reduction than targeting customers based solely on area code.


# Medium Question 2 - Customer Service Calls Threshold Analysis

## Business Question

Explore the relationship between the number of customer service calls and churn, considering different thresholds (e.g., more than 3 calls).

## Findings

### Customer Service Calls vs Churn Rate

| Customer Service Calls | Churn Rate |
|------------------------:|-----------:|
| 0 | 10.95% |
| 1 | 10.89% |
| 2 | 10.77% |
| 3 | 11.29% |
| 4 | 44.02% |
| 5 | 60.49% |
| 6 | 67.86% |
| 7 | 53.85% |
| 8 | 50.00%* |
| 9 | 100.00%* |

\* Churn rates for customers with 8 and 9 service calls are based on a very small number of customers and should be interpreted cautiously.

### Threshold Summary

| Customer Service Call Segment | Churn Rate |
|-------------------------------|-----------:|
| 0–3 Calls | 10.93% |
| 4+ Calls | 50.75% |

## Key Observation

The churn rate remains relatively constant at approximately **11%** for customers making up to three customer service calls. However, the churn rate increases sharply to **50.75%** for customers requiring four or more service calls, indicating a clear churn threshold.

## Business Insight

Repeated customer service interactions appear to be one of the strongest behavioral indicators of customer churn. Customers contacting customer support four or more times are nearly **five times more likely** to churn than customers who contact support three or fewer times.

## Recommendation

Introduce an automated customer retention workflow after a customer's **third customer service call**. Escalating these cases to experienced support representatives and proactively resolving unresolved issues before the fourth interaction could significantly reduce customer churn.


# Medium Question 3 - Account Length vs Churn (Quartile Analysis)

## Business Question

Investigate the relationship between account length and churn. Are newer customers more likely to churn?

---

## Findings

| Account Length Quartile | Churn Rate |
|--------------------------|-----------:|
| Q1 (Newest Customers) | 12.78% |
| Q2 | 14.33% |
| Q3 | 15.85% |
| Q4 (Longest Tenure) | 13.35% |

---

## Key Observation

The churn rate does not increase or decrease consistently across account length quartiles. The highest churn rate is observed in **Q3 (15.85%)**, while the newest customers (**Q1**) have the lowest churn rate (**12.78%**).

---

## Business Insight

The quartile analysis indicates that **account length alone has a weak relationship with customer churn**. Newer customers are not significantly more likely to churn, and customer tenure does not display a clear trend across the four groups.

---

## Recommendation

Avoid using account length as a primary indicator for churn prediction. Instead, combine account tenure with stronger behavioral factors such as customer service interactions, International Plan subscription, and daytime usage to identify high-risk customers more accurately.

# Medium Question 4 - International Call Charges vs Churn

## Business Question

Analyze the impact of international call charges on churn among subscribers of international plans.

---

## Findings

| International Charge Segment | Customers | Churn Rate |
|------------------------------|----------:|-----------:|
| High Charges | 216 | 48.61% |
| Low Charges | 180 | 34.44% |

---

## Key Observation

Customers with higher international call charges experience a churn rate that is **14.17 percentage points** higher than customers with lower international charges.

---

## Business Insight

Among customers subscribed to the International Plan, heavier spending on international calls is associated with a greater likelihood of churn. This may indicate that frequent international callers are more sensitive to pricing or perceive insufficient value from the current plan.

---

## Recommendation

Review international pricing strategies and introduce cost-effective international bundles, loyalty discounts, or usage-based offers for high-spending international customers to improve retention.


# Medium Question 5 - Evening Usage Patterns vs Churn

## Business Question

Examine how evening usage patterns (calls and charges) relate to customer churn.

---

## Findings

| Metric | Non-Churn | Churn |
|--------|----------:|-------:|
| Average Evening Calls | 100.23 | 99.84 |
| Average Evening Charges | 16.88 | 17.85 |

---

## Key Observation

The average number of evening calls is nearly identical for both customer groups. However, churned customers incur higher average evening call charges than non-churned customers.

---

## Business Insight

Evening call frequency does not appear to influence churn significantly. However, higher evening charges may contribute to customer dissatisfaction, suggesting that pricing has a greater impact on churn than call volume.

---

## Recommendation

Review evening call pricing and introduce attractive evening calling packages or loyalty discounts for customers with higher evening call charges to improve retention.


# Medium Question 6 - Customer Usage Segmentation vs Churn

## Business Question

Identify customer groups based on overall service usage patterns (day, evening, night, and international) and compare their churn rates.

---

## Findings

| Usage Segment | Customers | Churn Rate |
|--------------|----------:|-----------:|
| High Usage | 1417 | 22.58% |
| Medium Usage | 1416 | 7.20% |
| Low Usage | 1417 | 12.42% |

---

## Key Observation

High-usage customers have the highest churn rate, while medium-usage customers exhibit the lowest churn rate. The relationship between service usage and churn is not linear.

---

## Business Insight

Customers with heavy service usage are more likely to churn, possibly due to higher billing, increased expectations, or greater sensitivity to service quality. Medium-usage customers appear to represent the most stable customer segment.

---

## Recommendation

Develop premium retention strategies for high-usage customers, including personalized offers, loyalty incentives, and proactive customer support. Continue engaging medium-usage customers to maintain their strong retention levels.


# Medium Question 7 - Voice Mail Plan & Voice Mail Messages vs Churn

## Business Question

Analyze churn among customers with a Voice Mail Plan by comparing customers with high and low voice mail message usage.

---

## Findings

| Voice Mail Message Segment | Customers | Churn Rate |
|----------------------------|----------:|-----------:|
| High Usage | 529 | 8.51% |
| Low Usage | 583 | 6.35% |

---

## Key Observation

Customers with higher voice mail message usage exhibit a slightly higher churn rate than customers with lower usage. The difference is modest at **2.16 percentage points**.

---

## Business Insight

Voice Mail message usage has only a weak relationship with customer churn. While heavier users churn slightly more often, the difference is much smaller than the effects observed for customer service calls, international call charges, or overall service usage.

---

## Recommendation

Maintain Voice Mail services as a value-added feature, but prioritize retention strategies based on stronger churn indicators such as frequent customer service calls and high overall service usage.


### MQ8 - Payment Method Preference vs Churn

This question was not implemented because the provided telecommunications churn dataset does not contain any payment-related attributes (e.g., payment method, billing type, or billing frequency). To maintain analytical integrity, this analysis was omitted rather than making unsupported assumptions.


# Medium Question 9 - International Calls vs Churn by International Plan

## Business Question

Determine whether the number of international calls affects churn differently for customers with and without an International Plan.

---

## Findings

### International Plan = Yes

| International Call Segment | Customers | Churn Rate |
|---------------------------|----------:|-----------:|
| High | 156 | 32.69% |
| Low | 240 | 48.33% |

### International Plan = No

| International Call Segment | Customers | Churn Rate |
|---------------------------|----------:|-----------:|
| High | 1560 | 10.58% |
| Low | 2294 | 11.60% |

---

## Key Observation

Among customers with an International Plan, low international call usage is associated with substantially higher churn. For customers without an International Plan, international call volume has little impact on churn.

---

## Business Insight

Customers who subscribe to an International Plan but make relatively few international calls may not perceive enough value from the service, increasing their likelihood of churning. In contrast, international call volume has minimal influence on customers who do not subscribe to the plan.

---

## Recommendation

Monitor International Plan subscribers with consistently low international call usage and proactively offer plan optimization, customer education, or targeted retention offers to improve plan value and reduce churn.

# Medium Question 10 - Customer Service Call Reasons vs Churn

## Business Question

Explore whether different customer service call reasons are associated with different churn rates.

---

## Findings

The provided telecommunications dataset does not include customer service call reason information. It only records the total number of customer service calls made by each customer.

Therefore, this analysis could not be performed without introducing unsupported assumptions.

---

## Business Insight

Understanding the reason behind customer service interactions would provide valuable insights into the root causes of customer churn. Categories such as billing complaints, network issues, technical support requests, or service cancellations could help identify the most critical drivers of customer dissatisfaction.

---

## Recommendation

Enhance future data collection by recording customer service call categories. This additional information would enable more detailed churn analysis and support targeted service improvements.


# Medium Question 8 - Day Usage & Day Charges vs Churn

## Business Question

Investigate whether increasing daytime usage leads to higher churn and determine whether a tipping point exists.

---

## Findings

### Day Minutes Quartiles

| Quartile | Customers | Churn Rate |
|----------|----------:|-----------:|
| Q1 | 1063 | 12.14% |
| Q2 | 1062 | 9.13% |
| Q3 | 1063 | 6.21% |
| Q4 | 1062 | 28.81% |

The same churn pattern was observed for **Day Charges**, as day charges are directly proportional to day minutes in the dataset.

---

## Key Observation

Customer churn remains relatively low across the first three quartiles but increases sharply in the highest usage quartile, indicating a clear usage threshold where churn risk rises significantly.

---

## Business Insight

Heavy daytime users appear to have different service expectations or pricing sensitivities. Once customer usage reaches the highest quartile, churn increases substantially, suggesting that high-value users may require more suitable plans or proactive engagement.

---

## Recommendation

Monitor customers in the highest daytime usage quartile and proactively offer optimized pricing plans, usage-based recommendations, or loyalty incentives to reduce churn among heavy users.