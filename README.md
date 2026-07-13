# 🎬 Netflix Movies & TV Shows Data Analysis

An Exploratory Data Analysis (EDA) project that analyzes Netflix's catalog using Python, Pandas, NumPy, and Matplotlib to uncover trends in content type, countries, genres, ratings, release years, and movie durations.

---

## 📌 Project Overview

This project explores the Netflix Movies & TV Shows dataset through data cleaning, visualization, and exploratory analysis. The goal is to understand how Netflix's content library has evolved over time and identify key patterns in its catalog.

---

## 📂 Dataset

- **Source:** Kaggle - Netflix Movies and TV Shows Dataset
- **Records:** 8,807
- **Features:** 12

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📊 Questions Answered

- What is the distribution of Movies and TV Shows?
- Which countries contribute the most content?
- How has Netflix's library grown over time?
- What are the most common content ratings?
- What are the most popular genres?
- Which directors have the highest number of titles?
- What is the distribution of movie durations?
- How has content production changed over the years?

---

## 📈 Visualizations

### 1. Movies vs TV Shows

![Movies vs TV Shows](images/movies_vs_tvshows.png)

---

### 2. Top Contributing Countries

![Top Countries](images/top_countries.png)

---

### 3. Netflix Growth Over Time

![Growth](images/titles_added.png)

---

### 4. Content Ratings

![Ratings](images/ratings.png)

---

### 5. Popular Genres

![Genres](images/genres.png)

---

### 6. Top Directors

![Directors](images/directors.png)

---

### 7. Movie Duration Distribution

![Duration](images/duration.png)

---

### 8. Release Year Distribution

![Release Year](images/release_year.png)

---

## 🔍 Key Findings

- Movies make up a significantly larger portion of Netflix's catalog than TV Shows.
- The United States and India contribute the highest number of titles.
- Netflix expanded its catalog rapidly between 2016 and 2019.
- TV-MA and TV-14 are the most common content ratings.
- Drama and International genres dominate the platform.
- Most Netflix movies have durations between 80 and 120 minutes.
- The majority of titles available on Netflix were released during the last decade.

---

## 📁 Project Structure

```text
Netflix-Data-Analysis/
│
├── data/
│   └── netflix_titles.csv
│
├── images/
│   ├── movies_vs_tvshows.png
│   ├── top_countries.png
│   ├── titles_added.png
│   ├── ratings.png
│   ├── genres.png
│   ├── directors.png
│   ├── duration.png
│   └── release_year.png
│
├── notebooks/
│   └── Netflix_EDA.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Netflix-Data-Analysis.git
```

2. Install the required packages

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook notebooks/Netflix_EDA.ipynb
```

---

## 📌 Future Improvements

- Build an interactive dashboard using Streamlit or Plotly.
- Perform sentiment analysis on title descriptions.
- Develop a recommendation system based on genres and descriptions.
- Explore actor collaboration networks.
- Compare Netflix's catalog across different regions.

---

## 👨‍💻 Author

**Gauransh Pal**

- GitHub: https://github.com/Gauransh47
- LinkedIn: https://www.linkedin.com/in/gauransh-pal-11016b37a