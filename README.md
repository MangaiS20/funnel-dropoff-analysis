# User Funnel Drop-off Analysis

## Overview

This project analyzes a user signup and checkout funnel using Python and Pandas. The objective is to measure user conversion at each funnel stage, identify the largest drop-off point, and provide actionable business insights.

## Dataset

The dataset contains event-level records with the following columns:

- user_id
- step
- timestamp

Funnel stages:

1. Visited Site
2. Signup Started
3. Details Filled
4. Email Verified
5. Purchase Completed

## Tools Used

- Python
- Pandas
- Matplotlib
- Google Colab

## Analysis Performed

- Data exploration
- Unique users at each funnel stage
- Stage-to-stage conversion rate
- Drop-off rate calculation
- Funnel visualization
- Average time between valid consecutive stages
- Business insights and recommendations

## Key Findings

- Total users: **200**
- Largest drop-off occurred between **Details Filled** and **Email Verified**.
- Drop-off rate: **45.83%**

## Recommendation

Simplify the email verification process, provide clearer instructions, and send reminder emails to improve user retention and increase overall conversion.

## Repository Structure

```
Dataanalyst_assesment.ipynb
funnel_events_sample.csv
README.md
```

## Author

**Mangai S**
- MSc Data Science
- GitHub: https://github.com/MangaiS20
- LinkedIn: https://www.linkedin.com/in/mangais20
