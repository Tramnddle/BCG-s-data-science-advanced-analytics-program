# README

# BCG Open-Access Data Science & Advanced Analytics Virtual Experience Program

## Overview
The **BCG Open-Access Data Science & Advanced Analytics Virtual Experience Program** is designed to provide a realistic simulation of working at **BCG GAMMA**, where data science and advanced analytics are used to drive business transformation.

## Project: Customer Churn Analysis for PowerCo
Participants work on a case for **PowerCo**, a utility company facing declining profits due to customer churn in the **Small & Medium Enterprise (SME)** segment. The goal is to analyze customer churn, determine if price sensitivity is a key factor, and test the impact of a **20% discount** as a retention strategy.

## Tasks & Objectives

### 1. Business Understanding & Problem Framing
- Understand PowerCo’s business challenges.
- Formulate a hypothesis about price sensitivity as a churn driver.
- Define a data-driven approach to test the hypothesis.

### 2. Exploratory Data Analysis & Data Cleaning
- Analyze customer and pricing data.
- Handle missing values, duplicates, and outliers.
- Identify key patterns and trends:
  + The churn rate is lowest for both new and long-term customers.
  + Highest churn is concentrated around customers with 3 to 7 years of tenure, suggesting mid-life contracts are more at risk.
  + Low-volume customers dominate the customer base and seem to make up most churners.
  + High-volume outliers exist but are rare, and they appear less likely to churn — possibly due to better service terms or more personalized retention efforts.
  + Consumption levels alone don’t strongly distinguish churners from retainers, but may still play a role in a multi-variable model.
  + Customer cohorts from 2010–2012 are critical to analyze further for churn risk—large in volume with notable churn rates.
  + Early cohorts have high retention, potentially worth studying for retention best practices or segmentation.
  + A drop in new activations post-2012 may suggest internal changes, market saturation, or external competition—this period is worth investigating.

### 3. Feature Engineering
- Identify churn drivers.
- Create new features to improve model accuracy.

### 4. Modeling & Evaluation
- Develop predictive churn models.
- Evaluate model performance using appropriate metrics.
- Test the effect of a 20% discount on high-risk customers.

## Technical Skills & Tools Used
- **Python** (Pandas, NumPy) for data manipulation.
- **Machine Learning** (Random Forest, Logistic Regression) for churn prediction.
- **Data Visualization** for trend analysis.

## Result. In the simulation I:

- Completed a customer churn analysis simulation for BCG Gamma, demonstrating advanced data analytics skills, identifying essential client data and outlining a strategic investigation approach.
- Conducted efficient data analysis using Python, including Pandas and NumPy. Employed data visualization techniques for insightful trend interpretation.
- Completed the engineering and optimization of a random forest model, achieving an 85% accuracy rate in predicting customer churn.
- Completed a concise executive summary for the Associate Director, delivering actionable insights for informed decision-making based on the analysis.

## Result on the discount hypothesis:
- A 20% discount can effectively retain revenue, especially if applied strategically.

- Churn probability alone isn’t sufficient; revenue value of customers should also be considered.

- Future improvements may include:

- Optimizing both discount level and cut-off threshold (2D optimization).

- Modeling churn likelihood as a function of discount level to better predict customer response.

