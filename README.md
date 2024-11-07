# Marketing Analytics Case Study: Communication Channel Comparison

## Overview
This project analyzes the effectiveness of various communication channels, including **TV** and **Audio** channels, to determine their performance based on key marketing metrics. The analysis highlights each channel's impact, reach, and efficiency, offering insights for optimizing media spend.

## Key Findings
![image](https://github.com/user-attachments/assets/15713715-9459-46cd-9598-b9967c6e07f9)

1. **Channel Reach and Engagement**
   - **TV** achieved the highest reach among the channels analyzed, accounting for **65%** of the total audience reached.
   - **Audio** channels followed with a reach of **30%**, but with a significantly higher engagement rate per exposure than TV.

2. **Cost Efficiency**
   - **Cost per Thousand Impressions (CPM):**
     - TV: **$15** per thousand impressions.
     - Audio: **$10** per thousand impressions, making it the most cost-effective option for reaching large audiences.
   - **Cost per Engagement (CPE):**
     - TV: **$0.45** per engagement.
     - Audio: **$0.30** per engagement, emphasizing Audio's efficiency in driving engagement relative to cost.

3. **Model accuracy**
![image](https://github.com/user-attachments/assets/10d33908-3d20-4866-b0e3-b716fea20278)

R² Scores:

Train R² = 0.890: The model explains 89% of the variance in the training data, which suggests a good fit.
Test R² = 0.918: The model explains 91.8% of the variance in the test data, slightly higher than in the training set, indicating that the model generalizes well.
Residual Distribution:

The residuals (differences between actual and predicted values) are spread fairly symmetrically around the zero line, showing no strong pattern, which suggests that the model has captured the main trends without significant bias.
The histogram on the right shows the residual distribution, which appears roughly normal, suggesting that the model errors are randomly distributed. This is a good sign for linear regression as it indicates no significant skewness or outliers.
Model Fit:

The residuals tend to be closer to zero, which implies that predictions are relatively accurate. However, there are some data points with higher residuals, suggesting a few observations where the model’s predictions were less accurate

5. **Impact on Brand Metrics**
   - TV led to a **20% lift** in brand recall, compared to a **15% lift** from Audio.
   - Audio had a stronger effect on **purchase intent**, with a **25% increase** in intent scores following exposure.

## Insights and Recommendations

- **Optimize Spend on Audio for Younger Audiences:** Given Audio's effectiveness in reaching younger demographics at a lower CPM, shifting a portion of the budget from TV to Audio may improve cost efficiency without sacrificing reach in the 18-34 age group.
- **Leverage TV for Brand Recall:** The high brand recall associated with TV suggests it remains a valuable channel for branding campaigns, particularly for older demographics.
- **Increase Frequency on Audio:** Due to its higher engagement per exposure rate, a higher frequency of ads on Audio could enhance purchase intent and drive conversions among younger listeners.
