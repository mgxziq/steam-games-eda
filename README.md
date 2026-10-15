# Steam Games: Exploratory Data Analysis

An exploratory data analysis (EDA) of the Steam Store Games dataset, covering 27,075 games across 18 columns. The notebook looks at pricing, genres, platforms, ratings, release trends, ownership, playtime, and more.

## Questions Explored

- What types of games are on Steam?
- How are prices distributed, and how do they differ by genre?
- Which genres, platforms, and tags are the most common?
- What do user ratings look like?
- How has the number of releases changed over time?
- How many owners do most games have?

## Dataset

- **Source:** Steam Store Games dataset (Kaggle)
- **Size:** 27,075 rows x 18 columns
- **File used:** `steam.csv` (place it in the project root before running)

## Analysis Steps

1. Data loading and inspection
2. Missing value handling (only 15 missing values, filled with `Unknown`)
3. Feature engineering: `release_year`, `total_ratings`, `positive_pct`, `is_free`, `owners_estimate`
4. Price analysis (free vs paid, distribution, common price points)
5. Genre analysis (top genres, average price per genre)
6. Platform analysis (Windows, Mac, Linux)
7. Ratings analysis (distribution, top rated, most reviewed)
8. Release year trends and average price over time
9. Ownership analysis
10. Top developers and publishers
11. Playtime, language support, SteamSpy tags, and achievements
12. Correlation heatmap

## Key Findings

- About 9.5% of games are free; the remaining 90.5% are paid.
- Among paid games, the average price is $6.71 and the median is $4.79.
- Windows is supported by virtually all games; about 30% support Mac and 19% support Linux.
- Releases peaked in 2018 with 8,160 games.
- Most games (18,596) fall in the 0-20K owners range, so most titles have small audiences.
- Only 22.8% of games have recorded playtime data.
- 56.2% of games include achievements.

## Tech Stack

- Python 3
- pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## How to Run

```bash
git clone https://github.com/<your-username>/steam-games-eda.git
cd steam-games-eda
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook Steam_EDA.ipynb
```

Make sure `steam.csv` is in the same folder as the notebook.

## Project Structure

```
steam-games-eda/
├── Steam_EDA.ipynb
├── steam.csv
├── images/          # exported charts
└── README.md
```

## Author

Mohammed Akram Anwar
Artificial Intelligence Engineering Technologies, Northern Technical University
