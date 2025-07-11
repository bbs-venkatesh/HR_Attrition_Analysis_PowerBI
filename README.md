# HR Attrition Analysis Dashboard (Power BI)

## Project Overview

This project focuses on analyzing employee attrition within a company using HR data. The goal is to identify key factors contributing to employees leaving the organization and provide actionable insights to HR and management for improved retention strategies.

## Problem Statement

Employee attrition is a significant challenge for any organization, impacting productivity, morale, and recruitment costs. This analysis aims to understand the root causes of attrition by exploring various employee attributes and their relationship with the likelihood of leaving the company.

## Data Source

The dataset used for this analysis is a sample HR Analytics dataset sourced from Kaggle.
https://www.kaggle.com/datasets/mohammadkaiftahir/hr-analytics

## Tools Used

* **Excel:** For data cleaning, transformation and analysis.
* **MySQL:** Used as a relational database to store the cleaned and transformed dataset, serving as the data source for Power BI.
* **Power BI Desktop:** Utilized for interactive dashboard development and in-depth data visualization.


## Key Findings & Insights

Based on the analysis presented in the Power BI dashboard across its pages, here are some key insights discovered:

### 1. Overall Attrition Snapshot:
* The overall attrition rate for the company is **16.12%**.
* **Sales** department shows the highest attrition rate of **20.63%**.
* Employees who work **OverTime** are significantly more likely to attrit compared to those who do not.

### 2. Demographic & Satisfaction Impact:
* **Age:** Younger employees (18-24) with **35.77%** and those in early career stages (25-34) **19.14%** exhibit a higher tendency to attrit.
* **Marital Status:** Single employees show a disproportionately higher attrition rate **25.53%** compared to married or divorced employees.
* **Job Satisfaction:** A strong correlation exists between low Job Satisfaction scores (ratings 1 and 2) and a high likelihood of attrition. Employees reporting 'Low' Environment Satisfaction are also highly prone to leaving.
* **Job Involvement:** Lower Job Involvement scores are also associated with increased attrition.

### 3. Job Role, Performance & Tenure Insights:
* **Job Role & Level:** Attrition rates are notably higher in Job Roles like 'Sales Representative' and 'Laboratory Technician,' particularly at 'Job Level 1'.
* **Performance:** While attrition is present across all performance ratings, a surprising number of 'Outstanding' (Rating 4) performers are leaving, suggesting factors beyond performance are at play for top talent.
* **Tenure:** Attrition is most significant within the first 1-2 years of employment, indicating potential onboarding or early career development challenges. There's also a smaller peak around 5-7 years, possibly linked to career progression.

## Power BI Report Highlights

The interactive Power BI dashboard provides a drill-down capability to explore these insights further. Below are screenshots of the main report pages:

### Page 1: Overview / Executive Summary
https://github.com/bbs-venkatesh/HR_Attrition_Analysis_PowerBI/blob/main/Page1_Overview.png

### Page 2: Demographic & Satisfaction Impact
https://github.com/bbs-venkatesh/HR_Attrition_Analysis_PowerBI/blob/main/Page2_Demographic%20Influence.png

### Page 3: Attrition Deep Dive by Job Role, Performance & Tenure
https://github.com/bbs-venkatesh/HR_Attrition_Analysis_PowerBI/blob/main/Page3_Tenure.png

## Limitations & Future Work

Due to time constraints, this initial analysis focused on leveraging Power BI for exploratory data analysis and dashboarding. For future iterations, the project could be expanded to:

* **Predictive Modeling:** Integrate Python (with libraries like scikit-learn) to build and evaluate predictive models to forecast individual employee attrition risk.
* **Qualitative Data Integration:** Combine quantitative findings with qualitative data from exit interviews or employee surveys for richer, more nuanced insights.
* **Deeper Dive:** Further analyze factors like compensation competitiveness and specific team dynamics, which could not be fully explored in this scope.

## Conclusion
By analysing this HR data, this report clearly shows the main reasons behind staff leaving, including things like working overtime and how long they've been with us. These insights are very practical and will help us improve how we keep our talent.

## Author - BB Siva Venkatesh

This project is part of my portfolio, showcasing the MS PowerBI Dashboard skills essential for data analyst roles. If you have any questions, feedback, or would like to collaborate, feel free to get in touch!

- **LinkedIn**: [Connect with me professionally](https://www.linkedin.com/in/siva-venkatesh/)


Thank you for your support, and I look forward to connecting with you!
