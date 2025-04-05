# 📊 Netflix Dataset Analysis

This project explores and analyzes a dataset containing Netflix titles to uncover trends, patterns, and insights about the streaming platform's content over time. The goal is to answer questions like:  
- What types of content dominate Netflix?
- Which countries produce the most content?
- How has content evolved over the years?
- Who are the most frequent actors/directors?

---

## 📁 Dataset

The dataset used is publicly available on [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows).  
It contains information about movies and TV shows available on Netflix, including:

- Title  
- Type (Movie/TV Show)  
- Director & Cast  
- Country of origin  
- Release year  
- Date added to Netflix  
- Duration  
- Genre (listed in `category`)  

---

## 🔍 Exploratory Data Analysis (EDA)

Key steps performed:

- Data cleaning (handling nulls, standardizing formats)
- Feature engineering (e.g., extracting year from date_added)
- Univariate and multivariate analysis using:
  - Bar plots, pie charts
  - Word clouds
  - Heatmaps & time series plots

---

## 📌 Key Insights

- 📺 **TV Shows** are slightly more frequent than Movies in recent years.
- 🌍 Most content originates from the **United States**, followed by India and the UK.
- 🗓️ The number of new titles added peaked around **2019**.
- 🎬 The most frequent genre is **Documentaries**, followed by Dramas and Comedies.
- 👤 **David Attenborough** and **Steven Spielberg** are among the top contributors (director-wise).
- 📆 The **"date added"** field shows clear seasonal trends in content drops.

---

## 📦 Tech Stack

- Python (Pandas, NumPy)
  
---

## 🚀 Getting Started

### Prerequisites:
- Python 3.x
- Install required packages:

```bash
pip install -r requirements.txt
