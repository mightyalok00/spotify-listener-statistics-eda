# Spotify Listener Statistics Analysis

This project analyzes 500 Spotify listening records to identify patterns across countries, artists, genres, albums, release years, and subscription types. The analysis covers data quality, listener reach, streaming volume, engagement, recent performance, and skip behavior.

## Project Files

- [`Spotify.ipynb`](./Spotify.ipynb) — complete analysis with executed outputs and 15 visualizations
- [`Spotify_2024_Global_Streaming_Data.csv`](./Spotify_2024_Global_Streaming_Data.csv) — source dataset
- [`Spotify_2024_Cleaned_Data.csv`](./Spotify_2024_Cleaned_Data.csv) — cleaned dataset produced by the notebook
- [`Spotify Listener Statistics Final Report.docx`](./Spotify%20Listener%20Statistics%20Final%20Report.docx) — final findings, recommendations, methodology, and limitations
- [`Spotify Listener Statistics Analysis Presentation`](./Spotify_Listener_Statistics_Analysis_Presentation_By_Alok_Agarwal.pptx) — project presentation

## Business Questions

The project answers the following questions:

1. Which countries have the largest listener base and generate the most streams?
2. Which genres are popular across different countries?
3. Which artists lead total streams, monthly listeners, engagement, and recent activity?
4. Which albums and release years generate the strongest streaming performance?
5. How do Free and Premium listening patterns differ?
6. Which genres and artists have the lowest skip rates?
7. Is longer average stream duration associated with lower skip rates?
8. Which genre presents the strongest promotion opportunity?

## Workflow

1. Load and validate the source data.
2. Check missing values, duplicates, data types, categorical consistency, and potential outliers.
3. Clean text and numeric fields while preserving plausible high-performing observations.
4. Perform univariate and bivariate analysis.
5. Analyze regional, artist, genre, album, platform, engagement, and release-year performance.
6. Summarize the findings and business recommendations.

## Main Findings

- Sweden generated the highest total streaming volume.
- Russia had the largest aggregated monthly-listener base.
- France recorded the strongest regional engagement score.
- BTS led both total streams and monthly listeners.
- Dua Lipa led artist engagement and recent 30-day streaming activity.
- Classical led total genre streams and the composite promotion-opportunity ranking.
- Premium records generated more total streams and had a lower average skip rate than Free records.
- Average stream duration and skip rate had a correlation of `-0.022`, indicating no meaningful linear relationship.

These findings describe the supplied project dataset. Aggregated monthly-listener totals may include repeated listeners, and the observed relationships should not be interpreted as causal.

## Tools and Dependencies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- `pathlib`
- `IPython.display`
- Jupyter Notebook

## Running the Notebook

1. Download or clone this repository.
2. Keep `Spotify.ipynb` and `Spotify_2024_Global_Streaming_Data.csv` in the same directory.
3. Install the listed dependencies if they are not already available.
4. Open `Spotify.ipynb` in Jupyter Notebook or JupyterLab.
5. Run all cells from top to bottom.

The committed notebook has been executed successfully: all 38 code cells complete without syntax or runtime errors.
