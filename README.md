# A/B Testing Conversion and Hypothesis Testing Insights for Sales

This Jupyter Notebook provides an in-depth analysis of user behavior and conversion rates for Bluetooth speaker sales using A/B testing methodologies. It aims to generate actionable insights that can drive business decisions and optimize marketing strategies.

---

## 📌 Objectives

- Understand user interaction and behavior on landing pages.  
- Analyze conversion rates based on bounce flags and session metrics.  
- Evaluate the performance of different product pages and demographic segments.  
- Provide business recommendations based on data-driven insights.

---

## 📂 About This File

### Dataset Description

This dataset includes data from **30,000 user sessions**, featuring both returning and first-time visitors. The sessions are segmented by the **landing page variant** each user saw. The dataset allows for in-depth analysis of user behavior, conversion rates, and the impact of different landing page designs and demographics.

The dataset also includes user-specific details, session engagement, product purchases, and payment methods, providing a comprehensive view of how website features and user characteristics influence conversions.

### Columns
Dataset Available [Here](https://www.kaggle.com/datasets/sandeep1080/bassburst)

- **user_id**: Unique identifier for each visitor  
- **session_id**: Unique identifier for each session or visit  
- **sign_in**: Indicates if the user logged in via email or used guest access  
- **name**: Name of the visitor (generated from multiple locales)  
- **demographic_age**: Age of the visitor (14–80)  
- **demographic_age_group**: Age group ("Teenage", "Adult", "Old")  
- **demographic_gender**: Gender (Male, Female, Not Answered)  
- **email**: Email of user (if logged in)  
- **location**: City of the visitor  
- **country**: Country of the visitor  
- **device_type**: Device used (Mobile, Desktop, Tablet)  
- **timestamp**: Session start time  
- **variant_group**: Landing page design (Vibrant, Cold, Heat)  
- **time_spent**: Minutes spent on the landing page  
- **pages_visited**: Number of pages viewed in session  
- **conversion_flag**: Binary (0/1) if user converted  
- **conversion_type**: Type of conversion (Signup or Purchase)  
- **traffic_source**: Source of traffic (Organic, Paid, Social, Referral)  
- **product_purchased**: List of products purchased  
- **revenue**: Revenue generated from the transaction  
- **payment_type**: Payment method used (Card or COD)  
- **card_type**: Type of card used (Amex, Visa, Master)  
- **coupon_applied**: If a coupon was applied (Yes/No)  
- **bounce_flag**: If the session was a bounce (only one page visited)  

---

## 🧠 Key Analysis Sections

1. **Introduction**  
2. **Import Required Libraries**  
3. **Cleaning, Preprocessing, EDA**  
4. **Bounce Flag Analysis**  
5. **Bounce Flag Insights**  
6. **Business Suggestions - Bounce Flag**  
7. **Key Insights on Business Questions**  
8. **Landing Page Insights and Suggestions**  
9. **Product Performance Insights and Suggestions**  
10. **Other Factors Insights and Suggestions**

---

## 📊 Techniques Used

- Exploratory Data Analysis (EDA)  
- A/B Testing  
- Sequential Testing  
- Bayesian Inference  
- Revenue and Segment Analysis

---

## 👥 Target Audience

Marketing teams, data analysts, product managers, and business stakeholders who are interested in improving user engagement and conversion performance through experimentation.
