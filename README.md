
# Netflix Titles Exploratory Data Analysis (EDA)

This project explores the Netflix Titles dataset using Python. It includes data cleaning, transformation, visualization, and interpretation to discover trends and patterns in the content available on Netflix.

## Dataset

- Source: [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- File: `netflix_titles.csv`
- Size: ~8,800 rows, 12 columns

## Objectives

- Understand the distribution of content types (Movies vs TV Shows)
- Analyze trends over time (year content was added)
- Explore content ratings
- Discover top-producing countries
- Analyze most common genres
- Visualize duration patterns for movies and TV shows

## Tools Used

- Python 3
- pandas
- matplotlib
- seaborn
- collections (Counter)

## Key Insights

- Movies dominate Netflix’s catalog, with over twice the number of TV shows.
- Most content was added between 2016–2020, with a peak in 2018.
- TV-MA and TV-14 are the most common content ratings, targeting older teens and adults.
- The United States and India are the top content-producing countries.
- "International Movies", "Dramas", and "Comedies" are the most common genres.
- Most movies are around 90–100 minutes long.
- Most TV shows have only 1 season, indicating a high turnover or many limited series.

## Project Structure

```
netflix-eda/
├── data/
│   └── netflix_titles.csv
├── notebooks/
│   └── 01_exploratory_analysis.ipynb
├── output/
│   └── charts/
├── README.md
├── .gitignore
└── requirements.txt
```

## How to Run

1. Clone the repository
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```
   jupyter notebook notebooks/01_exploratory_analysis.ipynb
   ```

## Status

Completed — this EDA serves as a strong standalone portfolio project.
