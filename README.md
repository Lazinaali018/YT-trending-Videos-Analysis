# 📊 YouTube Trending Videos Analysis with Python

YouTube is the world’s most popular video-sharing platform, and understanding what makes a video trend can provide valuable insights for content creators and marketers.  
This project performs **exploratory data analysis (EDA)** on YouTube trending videos to identify patterns in titles, views, likes, comments, and overall engagement.

---

## 📌 Project Overview

- Analyzed YouTube trending video data collected over **205 days**
- Dataset contains **40,000+ trending videos**
- Identified trends in video titles, views, likes, and engagement
- Visualized correlations and patterns using Python data science libraries

---

## 📂 Dataset Information

- File used: `USvideos.csv`
- Data includes:
  - Video title
  - Views, likes, dislikes, comment count
  - Category ID
  - Description and metadata

---

## ⚙️ Technologies Used

- **Python**
- **Pandas & NumPy** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **WordCloud** – Text analysis
- **JSON & Datetime** – Data handling

---

## 🔍 Data Cleaning & Preprocessing

- Handled missing values in video descriptions
- Created new features such as:
  - Presence of capitalized words in titles
  - Length of video titles
- Formatted numeric values for improved readability

---

## 📊 Exploratory Data Analysis

### 🔹 Statistical Analysis
- Calculated summary statistics for views, likes, dislikes, and comments
- Identified skewed distributions and engagement patterns

### 🔹 Title Analysis
- Analyzed the effect of **capitalized words** in titles
- Studied **title length distribution** and its relationship with views

### 🔹 Correlation Analysis
- Visualized correlations using a **heatmap**
- Observed a strong positive correlation between **views and likes**

---

## ☁️ Text Analysis

- Generated a **Word Cloud** of trending video titles
- Identified commonly used words in high-performing videos

---

## 📈 Key Insights

- ~44% of trending videos contain at least one capitalized word in the title
- Most trending videos have title lengths between **30–60 characters**
- Title length shows **no strong correlation** with views
- Views and likes are **strongly positively correlated**

---

## 🚀 How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/lazinaali018/youtube-trending-analysis.git
