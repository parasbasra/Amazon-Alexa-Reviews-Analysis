# Amazon Alexa Reviews Analysis 📈

End-to-end analysis, sentiment classification, and business intelligence from thousands of Amazon Alexa product reviews. This project combines Python data science (NLP + machine learning) and Power BI interactive dashboarding to deliver actionable insights for product teams and executive stakeholders.

## 🚀 Project Overview

This project analyzes real-world Amazon Alexa product reviews to uncover:
- What drives customer satisfaction and complaints
- How sentiment, rating, and device type interact
- Key trends and product improvement opportunities

It demonstrates the full data analytics workflow: Python-based text and ML modeling, plus an executive-ready Power BI dashboard for exploration and storytelling.

## 🗂️ Data

- **Source:** Amazon Alexa Reviews Dataset (from Kaggle)
- **Fields:** date, device variation, rating, verified review, review text, computed sentiment, word count, and more
- **Scope:** Thousands of verified purchase reviews, spanning multiple Alexa device models/variations

## 🧰 Tools & Technologies

- **Python** (Pandas, scikit-learn, NLTK/VADER, XGBoost) for EDA, sentiment NLP, and model training
- **Power BI** for dashboarding, visual analytics, and stakeholder insights
- **Jupyter Notebook** for end-to-end data science workflow
- **Git/GitHub** for portfolio and version control

## ⚡ Workflow & Methodology

### 1. Data Preprocessing & Feature Engineering
- Cleaning and exploring raw review data
- Creating new features: review length, word count, NLP-based sentiment

### 2. Exploratory Data Analysis (EDA)
- Visualization of ratings, device variations, review characteristics
- Insights into distribution and trends

### 3. Sentiment Analysis & Machine Learning
- Rule-based and model-based sentiment labeling
- Multiple classifiers compared: Logistic Regression, XGBoost, Random Forest, Multinomial Naive Bayes
- Model evaluation: accuracy, classification reports, confusion matrices, and feature importances

### 4. Business Intelligence Dashboarding (Power BI)
- Interactive KPIs: total reviews, average rating, % positive, top device
- Distribution and trend visuals: ratings, sentiment, device variation, review length
- Drill-through detail view: read customer feedback filtered by device/sentiment
- Filters and slicers for flexible, executive-friendly slice-and-dice

## 📊 Key Insights

- Majority of Alexa reviews are positive (87%+), average rating ~4.5/5.
- Device models vary in satisfaction—some variants receive more criticism.
- Negative reviews are, on average, longer and more detailed.
- Sentiment and star ratings strongly correlate, but some high-star reviews contain nuanced complaints.
- Power BI dashboard enables business users to drill into real feedback for product, feature, and CX improvement.

## 📝 Project Structure

- **/notebooks/**
  - `alexa_review_analysis.ipynb` – Fully-commented, end-to-end Jupyter notebook (EDA, sentiment, ML modeling)
- **/dashboard/**
  - `alexa_review_dashboard.pbix` – Power BI dashboard file (interactive, executive-ready)
- **/data/**
  - `alexa_reviews_processed.csv` – Clean/prepared data for BI and sharing

## 📈 Sample Visuals

- Review count and star ratings distributions
- Sentiment over time (line/area)
- Stacked bar: device variation vs. sentiment
- Confusion matrices and model comparison bar charts
- Drill-through page: read individual customer comments

## 🛠️ How to Reproduce

1. Clone the repo, run the Jupyter notebook (`notebooks/alexa_review_analysis.ipynb`), and generate processed CSVs.
2. Open the processed data in Power BI (`dashboard/alexa_review_dashboard.pbix`).
3. Explore and filter insights interactively, or extend for new business questions.

## 💡 Business Value

This project empowers product managers, CX teams, and leadership to:
- Pinpoint areas for device improvement and support intervention
- Understand sentiment and usage trends across time and product line
- Translate unstructured feedback into actionable insights for Amazon Alexa evolution

## 👤 Author

[Paras Basra]
