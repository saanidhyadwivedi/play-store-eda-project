📱 Google Play Store Reviews – Data Analysis & Sentiment Insights
🔍 Project Overview

This project performs an end-to-end exploratory data analysis (EDA) and sentiment analysis on Google Play Store app data and user reviews to understand the key drivers of app success. The analysis combines quantitative metrics (ratings, installs, reviews, price) with qualitative signals (sentiment polarity & subjectivity from user reviews) to derive actionable business insights.

The goal is to move beyond vanity metrics (like installs alone) and provide a holistic, data-driven view of user satisfaction and engagement.

🎯 Business Objective

Identify key factors influencing app performance and user satisfaction

Understand how ratings, installs, reviews, and sentiment relate to each other

Perform category-level analysis to highlight performance differences

Provide actionable recommendations for product and growth teams

🧠 Problem Statement

Play Store hosts thousands of apps across diverse categories, but performance varies widely.
Stakeholders lack a structured understanding of:

What drives high installs vs high satisfaction

Whether ratings align with real user sentiment

Which categories show consistent quality vs high volatility

How to identify hidden dissatisfaction at scale

This project addresses these gaps using EDA and NLP-driven sentiment analysis.

🏗️ Project Architecture

The project follows a structured analysis workflow:

Problem Understanding & Assumptions

Data Cleaning & Preprocessing

Exploratory Data Analysis (EDA)

Sentiment Analysis on User Reviews

Correlation & Multivariate Analysis

Insight Generation & Business Recommendations

📊 Key Analysis & Visualizations

The project includes:

Distribution of Ratings

Sentiment Distribution (Positive / Neutral / Negative)

Rating vs Installs

Rating vs Price

Rating vs Sentiment Polarity

Review Count vs Sentiment Polarity

Category-wise Ratings & Sentiment (Box Plots)

Correlation Heatmap of App Metrics

Pair Plot for Multivariate Relationships

These visualizations were used to validate assumptions and derive insights.

💡 Key Insights

Higher installs are generally associated with higher review counts, but not necessarily with higher sentiment.

Ratings and sentiment polarity show positive alignment, validating sentiment analysis as a proxy for satisfaction.

Price does not strongly correlate with ratings, indicating that value perception matters more than pricing alone.

Categories show varying consistency in user experience, with some having higher volatility in ratings and sentiment.

Growth can occur without improvement in sentiment, highlighting long-term retention risk.

✅ Business Recommendations

Focus improvements on high-install but average/negative sentiment apps for maximum impact

Use sentiment tracking as an early-warning system for quality issues

Standardize UX and quality in high-variance categories

Improve feedback collection for high-install but low-review apps

Track engagement-adjusted growth metrics instead of installs alone

🛠️ Tech Stack

Python

Pandas, NumPy – Data cleaning & manipulation

Matplotlib, Seaborn / Plotly – Visualizations

NLTK / TextBlob – Sentiment Analysis

Jupyter Notebook – Analysis workflow
