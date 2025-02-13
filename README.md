# A/B Testing: Average Bidding vs. Maximum Bidding Strategy

## Overview
This analysis evaluates the impact of an **Average Bidding Strategy** (Test Campaign) versus a **Maximum Bidding Strategy** (Control Campaign) on key ad performance metrics. The goal is to determine whether the new bidding strategy improves ad efficiency and effectiveness.

## Problem
The company is testing a **new bidding strategy (Average Bidding)** to see if it **performs better than the existing Maximum Bidding Strategy** in terms of:
- Click-Through Rate (CTR)
- Conversion Rate (CR)
- Cost Per Mille (CPM)
- Cost Per Click (CPC)
- Cost Per Acquisition (CPA)

## Objective
- Compare the performance of the **Test Campaign** against the **Control Campaign**.
- Identify whether the **Test Campaign** significantly improves key ad performance metrics.
- Determine if the new bidding strategy is **cost-effective and conversion-efficient**.

## Key Steps
1. **Data Preparation**: Filtered campaign data for the Control and Test groups.
2. **Normality Testing**: Conducted **Shapiro-Wilk Test** to assess normality of performance metrics.
3. **Statistical Testing**: Since most metrics were **not normally distributed**, used **Mann-Whitney U Test (one-tailed)** to compare distributions.
4. **Analysis & Interpretation**: Evaluated whether the **Test Campaign** significantly outperforms the **Control Campaign**.

## Conclusions
- CTR (Click-Through Rate) is significantly higher in the Test Campaign (p = 0.000125), indicating the new bidding strategy attracts more clicks.
- CPM (Cost Per Mille) is also significantly higher (p = 0.0000006), suggesting that the new bidding strategy results in higher costs per 1,000 impressions.
- CR (Conversion Rate), CPC (Cost Per Click), and CPA (Cost Per Acquisition) show no significant differences, meaning the new strategy does not improve conversion efficiency.
- Key Trade-off: More clicks are generated, but at a higher cost per impression without a clear impact on conversions.

## Skills Demonstrated
- Statistical Testing (Shapiro-Wilk, Mann-Whitney U Test)
- Data Cleaning & Filtering
- A/B Testing & Experiment Evaluation
- Performance Metrics Interpretation
- Cost-Benefit Analysis of Bidding Strategies

## Technology Used
- Python (pandas, scipy, numpy)
- Statistical Hypothesis Testing
- Data Visualization (optional if needed)
