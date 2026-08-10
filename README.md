# User Funnel Drop-off Analysis

## Overview

This project analyzes a user signup and purchase funnel to understand how users move through different stages of the conversion journey.

The analysis focuses on measuring stage-wise conversion rates, identifying the major drop-off point, and generating business recommendations that can help improve user conversion and retention.

## Business Problem

Users may drop out at different stages of a signup or purchase journey. Identifying where the largest drop-off occurs can help businesses understand potential friction points and prioritize improvements.

This analysis answers the following questions:

- How many users reach each funnel stage?
- What is the conversion rate between consecutive stages?
- Where does the largest user drop-off occur?
- How much time do users spend between funnel stages?
- What actions could help improve the conversion rate?

## Objectives

- Analyze user movement through the funnel.
- Calculate the number of unique users at each stage.
- Measure stage-to-stage conversion rates.
- Calculate drop-off rates between consecutive stages.
- Identify the largest drop-off point.
- Analyze the average time between valid consecutive stages.
- Generate actionable business recommendations.

## Funnel Stages

The user journey consists of the following stages:

1. Visited Site
2. Signup Started
3. Details Filled
4. Email Verified
5. Purchase Completed

## Dataset

The dataset contains event-level user activity records.

### Columns

| Column | Description |
|---|---|
| `user_id` | Unique identifier for each user |
| `step` | Funnel stage completed by the user |
| `timestamp` | Date and time of the user event |

The dataset contains **200 unique users** and records their activity across the funnel stages.

## Tools & Technologies

- **Python**
- **Pandas** – data manipulation and analysis
- **Matplotlib** – data visualization
- **Google Colab** – development environment

## Analysis Approach

The analysis follows these steps:

1. Load and inspect the dataset.
2. Check the structure and quality of the data.
3. Identify unique users at each funnel stage.
4. Calculate stage-to-stage conversion rates.
5. Calculate drop-off rates.
6. Identify the stage with the highest drop-off.
7. Analyze the average time between valid consecutive stages.
8. Visualize the funnel performance.
9. Interpret the results and provide business recommendations.

## Key Findings

- The analysis covers **200 unique users**.
- User conversion decreases as users progress through the funnel.
- The largest drop-off occurs between **Details Filled** and **Email Verified**.
- The drop-off rate at this stage is **45.83%**.
- The email verification stage is therefore the primary area that should be investigated for potential user friction.

## Business Recommendation

Based on the funnel analysis, the email verification stage should be prioritized for improvement.

Possible actions include:

- Simplifying the email verification process.
- Providing clearer instructions to users.
- Making the verification step easier to understand.
- Sending reminder emails to users who have not completed verification.
- Investigating whether verification emails are delayed, missed, or difficult to access.

These improvements could help reduce user drop-off and increase overall funnel conversion.

## Project Structure

```text
funnel-dropoff-analysis/
│
├── Dataanalyst_assesment.ipynb
├── README.md
└── LICENSE
