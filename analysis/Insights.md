# Question 1 - Customer Churn Distribution

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