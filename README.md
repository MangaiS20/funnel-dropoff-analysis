# User Funnel Drop-off Analysis

##  Project Overview

This project analyzes user behavior across a multi-stage conversion funnel to understand how users progress from visiting a website to completing a purchase.

The analysis focuses on measuring the number of users reaching each funnel stage, calculating stage-to-stage conversion and drop-off rates, identifying the largest drop-off point, and generating actionable business recommendations.

---

##  Business Problem

Users may abandon a website or application at different stages of the conversion journey. Identifying where the largest drop-off occurs can help businesses understand potential friction points and prioritize areas for improvement.

This analysis aims to answer:

- How many users reach each funnel stage?
- What percentage of users progress from one stage to the next?
- Where does the largest drop-off occur?
- How much time do users take to move between consecutive stages?
- What actions could help reduce user drop-off?

---

##  Objectives

The main objectives of this analysis are to:

- Analyze user movement through the conversion funnel.
- Calculate the number of unique users at each stage.
- Calculate stage-to-stage conversion rates.
- Calculate drop-off rates between consecutive stages.
- Identify the stage with the largest drop-off.
- Analyze the average time taken between consecutive funnel stages.
- Provide actionable business recommendations based on the findings.

---

##  Funnel Stages

The user journey consists of five stages:

**Visited Site → Signup Started → Details Filled → Email Verified → Purchase Completed**

---

##  Dataset

The dataset contains event-level records representing user activity throughout the funnel.

### Dataset Columns

| Column | Description |
|---|---|
| `user_id` | Unique identifier for each user |
| `step` | Funnel stage associated with the event |
| `timestamp` | Date and time at which the user event occurred |

The analysis identifies **200 unique users** in the dataset.

---

##  Tools & Technologies

- **Python** – Data analysis and processing
- **Pandas** – Data manipulation and calculations
- **Matplotlib** – Data visualization
- **Google Colab** – Development environment

---

##  Analysis Approach

The analysis follows these steps:

1. Load and inspect the dataset.
2. Check the dataset structure, data types, missing values, and funnel stages.
3. Calculate unique users at each funnel stage.
4. Calculate stage-to-stage conversion rates.
5. Calculate drop-off rates between consecutive stages.
6. Identify the stage with the highest drop-off.
7. Analyze the average time taken between valid consecutive funnel stages.
8. Visualize the number of users at each funnel stage.
9. Interpret the results and provide business recommendations.

---

##  Funnel Analysis

The funnel analysis measures the number of unique users reaching each stage of the conversion journey.

| Stage | Funnel Step |
|---|---|
| 1 | Visited Site |
| 2 | Signup Started |
| 3 | Details Filled |
| 4 | Email Verified |
| 5 | Purchase Completed |

###  Major Drop-off

The largest drop-off occurs between **Details Filled** and **Email Verified**, with a **45.83% drop-off rate**.

This makes the email verification stage the primary area for further investigation and improvement.

---

##  Key Findings

### 1. User Conversion Decreases Throughout the Funnel

The number of users reaching each subsequent stage decreases as users progress through the conversion journey.

### 2. Email Verification Is the Major Drop-off Point

The highest drop-off occurs after users complete their details but before they verify their email.

The observed drop-off is **45.83%**.

### 3. Email Verification May Represent a Friction Point

The high loss of users at this stage suggests that the verification process may be creating friction in the user journey.

This stage should therefore be prioritized for further investigation.

---

##  Business Recommendations

Based on the funnel analysis, the following improvements could be considered:

### 1. Simplify the Verification Process

Reduce unnecessary steps involved in email verification so that users can complete the process more easily.

### 2. Enable One-Click Verification

A direct verification link can reduce the effort required from users to complete the verification step.

### 3. Send Reminder Emails

Users who have not completed verification could receive reminder emails to encourage them to return and finish the process.

### 4. Clearly Communicate the Purpose of Verification

Providing a short explanation of why email verification is required may increase user confidence and encourage completion.

### 5. Investigate Verification-Related Issues

Further investigation could determine whether users are experiencing:

- Delayed verification emails
- Difficulty locating verification messages
- Unclear verification instructions
- Other usability issues during the verification process

---

##  Visualization

The project includes a funnel visualization showing the number of unique users reaching each stage of the conversion journey.

The visualization helps identify the decline in users across the funnel and highlights the stages where user loss occurs.

---

##  Project Report

A detailed report documenting the project overview, business problem, methodology, funnel analysis, key findings, and business recommendations is included in this repository.

👉 [View Project Report](./Funnel_Dropoff_Analysis_Report.pdf)

---

## 📁 Project Structure

```text
funnel-dropoff-analysis/
│
├── Dataanalyst_assesment.ipynb
├── Funnel_Dropoff_Analysis_Report.pdf
├── README.md
└── LICENSE
```

##  How to Run

1. Clone or download this repository.
2. Open `Dataanalyst_assesment.ipynb` using Jupyter Notebook or Google Colab.
3. Make sure the required dataset is available in the expected location.
4. Run the notebook cells sequentially to reproduce the analysis.

---

##  Project Outcome

This project demonstrates the use of Python-based data analysis to evaluate a conversion funnel, identify user drop-off points, and translate analytical findings into practical business recommendations.

The analysis highlights the **Details Filled → Email Verified** transition as the major drop-off point, with a **45.83% drop-off rate**.

Improving the email verification experience could therefore be an important opportunity for reducing abandonment and improving overall funnel conversion.

---

##  Author

### Mangai S

**M.Sc. Data Science**

Aspiring **Data Analyst / Data Scientist** with an academic background in Data Science and Computer Science.

Interested in using data analysis, visualization, and machine learning techniques to solve business problems and generate actionable insights.

### 🔗 Connect With Me

- **GitHub:** [MangaiS20](https://github.com/MangaiS20)
- **LinkedIn:** [Mangai S](https://www.linkedin.com/in/mangais20)

---

##  License

This project is licensed under the MIT License.
