# A/B Testing Credit Card Promotions
# Project Title: A/B Testing Credit Card Promotions: Interest Rate Waiver vs. Standard Promotion
## Problem Statement:
### A financial institution recently launched a credit card promotion aimed at increasing purchases. To assess the effectiveness of this promotion, 500 randomly selected cardholders were divided into two groups:

###  Group A (Interest Rate Waiver): Received a promotion offering a full interest waiver on purchases for the next three months.
### Group B (Standard Promotion): Received a standard Christmas promotion without any special interest waiver.
 The goal of this project is to determine if the Interest Rate Waiver Promotion led to higher purchases compared to the Standard Christmas Promotion, utilizing A/B testing techniques and hypothesis testing.

## *Objective:*
To evaluate whether the Interest Rate Waiver Promotion is more effective than the Standard Promotion in driving purchases, using A/B testing and statistical analysis methods, including normality tests, variance tests, and t-tests.

## Methodology:
A/B Test Setup:

Group A (Interest Rate Waiver): Received the promotion offering the waiver of interest.
Group B (Standard Promotion): Received the standard Christmas promotion.
## *Normality Test (Shapiro-Wilk Test):*

H0 (Null Hypothesis): The data follows a normal distribution.     
Ha (Alternative Hypothesis): The data does not follow a normal distribution.
Result: Both data groups were found to be normally distributed.
## *Variance Test (Levene’s Test):*

H0: The variances of the two groups are equal.                    
Ha: The variances of the two groups are unequal.
Result: The p-value from the test was 0.287, indicating that the variances are equal.
## *Two-Sample T-Test:*

H0: The average purchases from both promotions are equal.          
Ha: The average purchases from both promotions are unequal.
Result: The p-value from the test was 0.024, meaning we reject the null hypothesis. Thus, the average purchases from both promotions are significantly different.
## *One-Tailed T-Test (Greater Alternative):*

H0: The average purchases from the Interest Rate Waiver Promotion are less than or equal to those from the Standard Promotion.                                             
Ha: The average purchases from the Interest Rate Waiver Promotion are greater than those from the Standard Promotion.
## Result: The p-value was 0.012, indicating that the Interest Rate Waiver Promotion resulted in higher purchases.

## *Conclusion:*
Based on the A/B test, the Interest Rate Waiver Promotion resulted in significantly higher purchases compared to the Standard Promotion. This analysis provides evidence that the interest rate waiver was a more effective strategy for increasing credit card purchases.

## Installation
1. **Clone the Repository**:

    `git clone https://github.com/MounikaGandla-01/A-B-Testing-Credit-Card-Promotions.git`
    
2. **Set Up Virtual Environment**:
    
   `python3 -m venv venv`

    `venv\Scripts\activate`

3. **Install Dependencies**:
   
   `pip install -r requirements.txt`

## Technologies and Libraries Used:
### Python: For data analysis and statistical testing.
### Key Libraries:
### scipy.stats: For performing statistical tests (Shapiro-Wilk test, Levene’s test, t-tests).
### pandas: For data manipulation and analysis.
### numpy: For numerical operations.


This project is a great demonstration of using A/B testing to evaluate the impact of different marketing strategies on customer behavior. It showcases:

How statistical techniques can be applied to business problems.
The process of hypothesis testing in real-world scenarios.
Understanding of experimental design (A/B testing), data-driven decision-making, and the ability to evaluate promotional effectiveness