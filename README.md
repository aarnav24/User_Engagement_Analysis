# 🍽️ User Engagement Analysis for Restaurant Success

A data analytics project using the Yelp dataset to understand how **user engagement (reviews, tips, check-ins)** impacts restaurant success and customer behavior.

---

## 🚀 Overview

In a competitive restaurant industry, understanding the relationship between customer engagement and business success is critical.

This project analyzes large-scale Yelp data to uncover:

- How engagement influences ratings and popularity  
- The role of sentiment in customer perception  
- Time-based trends and seasonal patterns  
- The impact of elite users on business growth  

---

## 🧠 Problem Statement

Analyze whether higher user engagement (reviews, tips, check-ins) leads to better business outcomes such as higher ratings and increased visibility.

---

## 🎯 Key Objectives

- Measure correlation between engagement metrics and ratings  
- Analyze sentiment impact (useful, funny, cool)  
- Identify time-based engagement trends  
- Compare engagement across cities and user segments  

---

## 🛠️ Tech Stack

- **Languages:** Python, SQL  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Database:** SQLite  
- **Data Source:** Yelp Open Dataset  

---

## 📊 Data Pipeline

- Loaded large JSON datasets (business, review, user, tip, check-in)  
- Stored structured data into **SQLite database**  
- Performed **multi-table joins and aggregations using SQL**  
- Conducted analysis using Python for visualization and insights  

---

## 🔍 Key Analysis Performed

- 📈 Engagement vs Ratings Analysis  
- 🔗 Correlation between reviews, tips, and check-ins  
- 🧑‍💼 Elite vs Non-Elite User Contribution  
- 🕒 Time Series & Seasonality Analysis (including COVID impact)  
- 🌍 Geographic Analysis across cities  
- 💬 Sentiment Analysis using engagement metrics  

---

## 📌 Key Insights

- Restaurants with ~4-star ratings show **highest engagement levels**  
- Reviews, tips, and check-ins are **strongly correlated**  
- Elite users contribute disproportionately to total engagement  
- Peak engagement hours occur between **4 PM – 1 AM**  
- Engagement trends show seasonal patterns and a dip during COVID  
- Higher engagement does not always guarantee higher ratings  

---

## 💡 Business Recommendations

- Focus on maintaining high ratings to maximize engagement  
- Leverage **elite users** for visibility and growth  
- Optimize staffing during peak hours (evening to late night)  
- Expand in high-performing cities  
- Encourage user interaction across all engagement channels  

---

## 📁 Project Structure

```bash
User_Engagement_Analysis/
│
├── notebooks/
│   ├── ingestion_db.ipynb
│   ├── User_Engagement_Analysis.ipynb
│
├── reports/
│   ├── User_Engagement_Report.pdf
│
├── README.md
```
