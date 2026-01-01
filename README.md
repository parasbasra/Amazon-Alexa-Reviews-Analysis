# Amazon Alexa Reviews Analysis 📊

Customer feedback analysis and business insights derived from Amazon Alexa product reviews.  
This project focuses on understanding customer sentiment, review patterns, and product perception using Python-based analysis and an interactive Power BI dashboard.

---

## 🚀 Project Overview

This project analyzes real-world Amazon Alexa customer reviews to answer business questions such as:
- What drives customer satisfaction and dissatisfaction?
- How do ratings and sentiment vary across device variations?
- What patterns in customer feedback can inform product and CX improvements?

The emphasis of the project is **exploratory analysis and insight generation**, with standard sentiment analysis techniques used as a supporting tool rather than as a modeling exercise.

---

## 🗂️ Data

- **Source:** Amazon Alexa Reviews Dataset (Kaggle)
- **Content:** Customer reviews, ratings, device variations, review text, and derived attributes
- **Scope:** Thousands of verified purchase reviews across multiple Alexa device models

---

## 🧰 Tools & Technologies

- **Python** (Pandas, scikit-learn, NLTK/VADER) for data cleaning, EDA, and sentiment analysis
- **Power BI** for interactive dashboards and business storytelling
- **Jupyter Notebook** for structured analysis workflow
- **Git/GitHub** for version control and portfolio presentation

---

## ⚙️ Analysis Workflow

### 1. Data Preparation & Exploration
- Cleaning and understanding raw customer review data
- Feature creation such as review length and sentiment labels
- Initial exploration of ratings, devices, and review characteristics

### 2. Exploratory Data Analysis (EDA)
- Distribution of ratings and sentiment
- Review length and feedback patterns
- Comparison of customer sentiment across device variations
- Identification of trends and anomalies in customer feedback

### 3. Sentiment Analysis (Supporting Analysis)
- Application of standard, off-the-shelf sentiment techniques to categorize customer feedback
- Sentiment used to validate patterns observed during EDA rather than to optimize predictive performance

### 4. Business Intelligence Dashboard (Power BI)
- KPIs: total reviews, average rating, sentiment distribution
- Interactive visuals by device variation and sentiment
- Drill-through capability to explore individual customer comments
- Designed for business users and stakeholders

---

## 📊 Key Insights

- Most Alexa reviews are positive, with high overall customer satisfaction.
- Certain device variations receive comparatively more negative feedback.
- Negative reviews tend to be longer and more detailed than positive ones.
- Sentiment generally aligns with star ratings, but qualitative feedback provides additional nuance.
- The Power BI dashboard enables stakeholders to explore customer feedback at both summary and detail levels.

---

## 🗂️ Project Structure

- **/1.data/**
  - Processed review data used for analysis and dashboarding
- **/2.dashboard/**
  - `alexa_review_dashboard.pbix` – Interactive Power BI report
- **/notebooks/**
  - `alexa_review_analysis.ipynb` – Python notebook containing data preparation, EDA, and sentiment analysis

---

## 💡 Business Value

This analysis demonstrates how unstructured customer feedback can be translated into actionable insights to support:
- Product improvement discussions
- Customer experience analysis
- Data-driven decision-making for product and CX teams

---

## 👤 Author

Paras Basra
