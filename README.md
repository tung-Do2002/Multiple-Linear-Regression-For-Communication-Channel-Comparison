# Marketing Analytics Case Study: Communication Channel Comparison

## Overview
This project analyzes the effectiveness of various communication channels, including **TV** and **Audio** channels, to determine their performance based on key marketing metrics. The analysis highlights each channel's impact, reach, and efficiency, offering insights for optimizing media spend.

## Key Findings

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

3. **Audience Demographics**
   - **TV** was particularly effective among the **35-50 age group**, representing **40%** of total engagements from this demographic.
   - **Audio** channels had a younger demographic skew, with **55%** of its audience in the **18-34 age range**.

4. **Impact on Brand Metrics**
   - TV led to a **20% lift** in brand recall, compared to a **15% lift** from Audio.
   - Audio had a stronger effect on **purchase intent**, with a **25% increase** in intent scores following exposure.

## Insights and Recommendations

- **Optimize Spend on Audio for Younger Audiences:** Given Audio's effectiveness in reaching younger demographics at a lower CPM, shifting a portion of the budget from TV to Audio may improve cost efficiency without sacrificing reach in the 18-34 age group.
- **Leverage TV for Brand Recall:** The high brand recall associated with TV suggests it remains a valuable channel for branding campaigns, particularly for older demographics.
- **Increase Frequency on Audio:** Due to its higher engagement per exposure rate, a higher frequency of ads on Audio could enhance purchase intent and drive conversions among younger listeners.

## Usage
This notebook contains code for importing, cleaning, and analyzing data related to media channel performance. Each step includes comments to guide users in understanding the analysis process and customizing it for other datasets.

```python
# Example Code Block from Analysis
import pandas as pd

# Load data
data = pd.read_csv("channel_performance.csv")

# Basic summary of channel performance
channel_summary = data.groupby('Channel').agg({
    'Reach': 'sum',
    'Engagement': 'mean',
    'CPM': 'mean'
})
print(channel_summary)
