# 📸 Instagram Reach & Engagement Analysis

A Data Analytics project that analyzes Instagram post performance, engagement metrics, and reach insights using Python, Data Visualization, and Machine Learning.

---

# 🚀 Project Overview

This project focuses on analyzing Instagram engagement data to understand:

- Reach and impressions
- User engagement behavior
- Traffic sources
- Profile conversion rate
- Relationship between likes, comments, shares, saves, and impressions
- Predicting Instagram impressions using Machine Learning

The analysis is performed using Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, Plotly, and Scikit-learn.

---

# 📂 Dataset

Dataset Used: `Instagram data.csv`

The dataset contains Instagram post analytics such as:

- Impressions
- Likes
- Comments
- Shares
- Saves
- Profile Visits
- Follows
- Reach Sources

---

# 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- WordCloud

---

# 📊 Analysis Performed

## ✔️ Data Cleaning
- Checked missing values
- Removed null values
- Dataset inspection using `.info()`

## ✔️ Exploratory Data Analysis (EDA)
Analyzed:
- Distribution of impressions from:
  - Home
  - Hashtags
  - Explore
- Instagram reach sources using Pie Chart
- Correlation between engagement metrics

## ✔️ Data Visualization
Created visualizations such as:
- Distribution plots
- Scatter plots
- Correlation heatmaps
- Pie charts
- WordCloud from Instagram captions

## ✔️ Engagement Analysis
Studied relationships between:
- Likes vs Impressions
- Comments vs Impressions
- Shares vs Impressions
- Saves vs Impressions
- Profile Visits vs Followers Gained

## ✔️ Conversion Rate Analysis
Calculated Instagram conversion rate using:

```python
(Follows / Profile Visits) * 100
```

## ✔️ Machine Learning Model
Used `PassiveAggressiveRegressor` to predict Instagram impressions based on:

- Likes
- Saves
- Comments
- Shares
- Profile Visits
- Follows

---

# 📈 Visualizations Included

- Distribution of Impressions
- Reach Source Analysis
- Engagement Scatter Plots
- Correlation Heatmap
- Caption WordCloud
- Followers vs Profile Visits Analysis

---

# 📌 Key Insights

- Home feed generated a large portion of impressions
- Engagement metrics strongly affect reach
- Saves and shares contribute significantly to impressions
- Profile visits influence follower conversion
- Machine Learning can estimate Instagram impressions effectively

---

# 🤖 Machine Learning Used

### Model:
- PassiveAggressiveRegressor

### Target Variable:
- Impressions

### Features Used:
- Likes
- Saves
- Comments
- Shares
- Profile Visits
- Follows

---

# 🎯 Future Improvements

- Add more Machine Learning models
- Build a Streamlit dashboard
- Deploy as a web application
- Add sentiment analysis on captions
- Real-time Instagram analytics integration

---

# 👨‍💻 Author

## Dhruv Rapariya

---

# ⭐ Support

If you like this project, don't forget to give it a ⭐ on GitHub!
