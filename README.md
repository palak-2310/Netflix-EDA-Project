# 🎬 Netflix Movies & TV Shows Exploratory Data Analysis (EDA)

A complete Exploratory Data Analysis (EDA) project on the Netflix Titles dataset using Python, Pandas, NumPy, and Matplotlib.

This project focuses on cleaning the dataset, engineering useful features, and discovering insights about Netflix's content library through visualizations.

---

## 📌 Project Overview

The objective of this project is to analyze Netflix's catalog and answer questions such as:

- What percentage of Netflix content is Movies vs TV Shows?
- How has Netflix's content grown over the years?
- Which genres are most common?
- Which countries contribute the most content?
- What are the most common content ratings?
- How old is content when it gets added to Netflix?

---

## 📂 Dataset

**Dataset:** Netflix Titles Dataset

Contains information such as:

- Show ID
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genres
- Description

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

---

## 📊 Project Workflow

### 1️⃣ Data Cleaning

- Loaded dataset
- Checked missing values
- Removed duplicates
- Converted dates to datetime
- Handled null values
- Created clean dataset

---

### 2️⃣ Feature Engineering

Created new features including:

- Year Added
- Month Added
- Duration (Minutes)
- Duration (Seasons)
- Primary Country
- Primary Genre
- Age Gap (Year Added − Release Year)

---

### 3️⃣ Exploratory Data Analysis

Performed analysis on:

### Content Type

- Movies vs TV Shows
- Percentage distribution
- Content growth over years

### Time Analysis

- Titles added every year
- TV Shows percentage over time
- Average age gap before appearing on Netflix

### Genre Analysis

- Top Genres
- Genre distribution

### Country Analysis

- Top producing countries
- United States vs Rest of World

### Rating Analysis

- Rating distribution
- Kids vs Teens vs Adults content

---

## 📈 Visualizations

The project includes multiple charts such as:

- Bar Charts
- Line Charts
- Pie Charts

All figures are exported as PNG images.

---

## 📁 Project Structure

```
Netflix-EDA/
│
├── Netflix.ipynb
├── netflix_titles.csv
├── outputs/
│   ├── cleaned_netflix.csv
│   ├── movie_vs_tv.png
│   ├── content_growth.png
│   ├── top_genres.png
│   ├── top_countries.png
│   ├── ratings_distribution.png
│   └── us_vs_rest.png
│
├── README.md
└── requirements.txt
```

---

## 📌 Key Insights

- Movies make up the majority of Netflix's catalog.
- Netflix experienced rapid content growth after 2015.
- Drama and International Movies are among the most common genres.
- The United States contributes the largest number of titles.
- TV-MA is the most frequent content rating.
- Most content is added within a few years of its original release.

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/Netflix-EDA.git
```

2. Install dependencies

```bash
pip install pandas numpy matplotlib
```

3. Open

```
Netflix.ipynb
```

4. Run all cells.

---

## 📷 Sample Visualizations

- Movie vs TV Show Distribution
- Content Added by Year
- Top Genres
- Top Countries
- Rating Distribution
- US vs Rest of World

---

## 🚀 Future Improvements

- Interactive Dashboard using Power BI or Tableau
- Plotly interactive visualizations
- Recommendation system
- Sentiment analysis on descriptions
- Predictive analysis using Machine Learning

---
