# IMDb Movies & TV Shows - Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on an IMDb Movies and TV Shows dataset using Python. The analysis includes data cleaning, descriptive statistics, visualization, correlation analysis, and outlier detection to uncover trends and patterns in movie and television data.

---

## Objectives

* Clean and prepare the dataset
* Handle missing values
* Check for duplicate records
* Analyze release trends over time
* Identify the most common genres
* Compare Movies and TV Series
* Investigate the relationship between popularity and ratings
* Detect outliers using the IQR method
* Generate meaningful business insights

---

## Dataset Features

* Title
* Title Type
* Genres
* Release Year
* Average Rating
* Number of Votes

---

## Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Exploratory Data Analysis

The following analyses were performed:

* Data Cleaning
* Missing Value Handling
* Duplicate Detection
* Movies Released Over Time
* Top 10 Years by Number of Releases
* Most Common Genres
* Movies vs TV Series Comparison
* Average Rating by Title Type
* Correlation Analysis
* Scatter Plot of Ratings vs Votes
* Correlation Heatmap
* Outlier Detection using Boxplots

---

## Key Insights

* Drama is the most common genre in the dataset.
* Movie production increased significantly after the early 2000s.
* Movies appear more frequently than TV series.
* TV series have a slightly higher average rating than movies.
* The relationship between popularity (number of votes) and audience rating is weakly positive.
* Several blockbuster titles have exceptionally high vote counts, making them valid outliers.
* Most audience ratings fall between 6 and 8.

---

## Project Structure

```
IMDb-EDA/
│
├── data/
│   └── title.combined.csv
│
├── notebooks/
│   └── IMDb_EDA.ipynb
│
├── images/
│   ├── releases_per_year.png
│   ├── top_genres.png
│   ├── movie_vs_tvseries.png
│   ├── ratings_vs_votes.png
│   └── boxplots.png
│
├── README.md
│
└── requirements.txt
```

---

## Future Improvements

* Genre-wise rating analysis
* Machine Learning models for rating prediction
* Recommendation system based on genres and ratings

---

## Author

**Ashhal**

Aspiring Data Scientist | Python | Data Analytics | Machine Learning

