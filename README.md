# Facebook Ads Performance Analysis

This project analyzes Facebook advertising campaign data using Python, Pandas, Matplotlib, and Seaborn.

The main goal is to explore campaign performance, visualize advertising trends, compare ROMI across campaigns, and examine relationships between numerical marketing metrics.

## Dataset

The dataset contains Facebook advertising campaign statistics with the following columns:

- `ad_date`
- `campaign_name`
- `total_spend`
- `total_impressions`
- `total_clicks`
- `total_value`
- `cpc`
- `cpm`
- `ctr`
- `romi`

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Overview

### 1. Daily Advertising Performance in 2021

The dataset was filtered for the year 2021 and grouped by date.

The analysis includes:

- Daily total advertising spend
- Daily average ROMI
- 7-day rolling average for advertising spend
- 7-day rolling average for ROMI

### 2. Campaign-Based Performance Analysis

The data was grouped by campaign name to compare campaign performance.

The analysis includes:

- Total advertising spend by campaign
- General ROMI by campaign

General ROMI was calculated as:

```python
general_romi = total_value / total_spend
