# British-Airways-Customer-Insights
Analyzing customer reviews and booking data for British Airways to provide acctionable insights using NLP and machine learning.
Here’s a well-structured README.md for your British Airways Customer Insights project.


---

# British Airways Customer Insights

## 📊 A data-driven approach to understanding customer feedback and booking patterns at British Airways.

# 📌 Project Overview

This job simulation involved working as a Data Scientist at British Airways, analyzing customer reviews and booking data to provide actionable insights. The project included web scraping, natural language processing (NLP), machine learning, and visualization to help the company improve customer experience and boost booking rates.


---

## 📌 Task 1: Customer Reviews Analysis

### ✈ Objective: Scrape, clean, and analyze customer feedback from Skytrax to identify key sentiment trends.

**🔹 Steps Performed:**

✅ Scraped customer reviews using BeautifulSoup.
✅ Cleaned text by removing stopwords, lemmatization, and handling missing values.
✅ Sentiment Analysis:

Positive Sentiment: 759 mentions

Negative Sentiment: 422 mentions

Neutral Sentiment: 19 mentions
✅ Topic Modeling (LDA): Identified key topics in customer feedback.


### 🔹 Key Insights:

Top Positive Words: flight, seat, service

Top Negative Words: flight, seat, delays

Main Pain Points: Flight delays & seat comfort issues.



## 📌 Task 2: Customer Booking Prediction Model

### ✈ Objective: Build a predictive model to analyze booking behavior and identify factors influencing ticket purchases.

**🔹 Dataset Overview:**

Size: 50,000 rows, 14 columns

Key Features: num_passengers, trip_type, route, booking_origin, flight_duration, etc.


**🔹 Data Processing & Feature Engineering:**

✅ Created new features:

is_weekend, booking time pattern, total extra services requested, popular flight routes, passenger count
✅ Handled categorical variables with label encoding & manual mapping.
✅ Applied scaling & SMOTE for class balancing.


**🔹 Model Performance:**

**Random Forest**: Accuracy 84.0%, ROC AUC 74.6% (Tuned: Accuracy 84.0%, ROC AUC 74.6%)

**XGBoost**: Accuracy 84.3%, ROC AUC 77.1% (Tuned: Accuracy 84.3%, ROC AUC 77.1%)

**LightGBM (Best Model)**: Accuracy 85.0%, ROC AUC 78.4% (Tuned: Accuracy 85.0%, ROC AUC 78.4%)

**🔹 Key Insights:**

📌 Top 5 Influencing Features:
1️⃣ Booking Origin
2️⃣ Route
3️⃣ Flight Duration
4️⃣ Length of Stay
5️⃣ Total Extra Services Requested


## 🚀 Business Recommendations & Actionable Insights

💡 Marketing Strategy: Focus advertising efforts on top booking origins & popular routes.
💡 Customer Experience: Address issues related to flight delays and seat comfort based on customer feedback.
💡 Revenue Boost: Encourage customers to purchase extra services by optimizing pricing strategies.



---

⭐ If you find this project insightful, give it a star on GitHub! ⭐
