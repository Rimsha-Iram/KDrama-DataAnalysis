# 🎬 K-Drama Netflix EDA (1995–2023)
A Data-Driven Exploration of Trends, Genres, and Viewer Preferences

An exploratory data analysis project focused on Korean Dramas available on Netflix between 2015 and 2023. This notebook explores content trends, genre distribution, actor frequency, ratings, and thematic patterns to uncover how the K-Drama industry has evolved over recent years.

---

## 🔍 Objectives

- Perform in-depth EDA on a curated dataset of K-Dramas.
- Analyze trends across genres, ratings, actors, and platforms.
- Visualize how K-Dramas have grown over time in both quality and quantity.
- Uncover insights from both structured (ratings, genres) and unstructured (plots) data.

---

## 📂 Dataset Overview

- **Source**: From kaggle.
- **Time Frame**: 1995 to 2023
- **Columns**:
  - Title
  - Release Year
  - Genre
  - Actors
  - Rating
  - Description (Plot Summary)
  - Age Category / Platform

- Initial steps included:
  - Loading and inspecting data structure
  - Handling missing values & duplicates
  - Cleaning genres, actors, and text fields
  - Type conversions (e.g., rating as float, year as int)

---

## 📊 Univariate Analysis

- **Genre Breakdown**: Most common genres across all dramas
- **Tag/Theme Frequencies**: Extracted from plots and titles
- **Rating Distribution**: KDE and histogram views of viewer ratings
- **Year-wise Drama Count**: Trends in yearly production
- **Visual Tools**: Barplots, pie charts

---

## 📈 Bivariate & Multivariate Analysis

- **Ratings Over Time**: Do newer dramas score better?
- **Genre vs. Rating**: Which genres perform best?
- **Platform Comparison**: Ratings across different OTT platforms
- **Tools**: Scatterplots, grouped barplots, heatmaps

---

## 📺 Platform Popularity

- **Drama Count per Platform**: Netflix, Viki, iQIYI, etc.
- **Platform vs. Genre**: Heatmap showing genre dominance by platform
- **Growth Trend**: Rise of specific platforms over time

---

## 🌟 Ratings vs. Age Category

- Compared average ratings of:
  - 18+ content vs. General Audience
  - Distribution shown via KDE and violin plots

---

## 🧠 Text-Based Insights

- **WordClouds** from drama descriptions
- **Theme Frequency Analysis** via text patterns
- Insights into recurring motifs (e.g., revenge, healing, school life)
  
---

## 📋 Key Takeaways

- K-Drama production surged post-2020, aligned with global streaming demand.
- Slice-of-life, romance, and thrillers emerged as top genres.
- Ahn Hyo-seop and Kim Se-jeong were among the most frequent lead actors.
- Viewer ratings remained high across genres, with a notable preference for emotional, healing narratives.
- Platforms like Viki and iQIYI are increasingly competing with Netflix in recent years.

---

## 📁 Project Files

```
KDrama_Netflix_EDA/
├── KDrama_EDA_1995_2023.ipynb   # Main analysis notebook     
└── README.md                    # Project overview 
```

---

## 🛠 Tools & Technologies

- **Python**
- **Pandas, NumPy** – Data Cleaning & Analysis
- **Seaborn, Matplotlib** – Visualizations
- **WordCloud** – Textual insights
- **Jupyter Notebook** – Development Environment

---

## 🔗 Connect

- **GitHub**: [Rimsha-Iram](#)
- **LinkedIn**: [www.linkedin.com/in/rimsha-iram-841905367](#)

---
