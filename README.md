# Spotify Music Trends & Popularity Analysis

**Business Intelligence | SQL · Power BI · DAX · Excel · Python**

A collaborative university project analyzing **11,762 Spotify tracks** to explore music popularity, audio characteristics, genres, and artist performance. The project combines data preparation, dimensional modeling, and an interactive three-page Power BI report to support music-industry decision-making.

**[📊 View the dashboard preview (PDF)](powerbi/dashboard_preview.pdf)** · [Power BI report](powerbi/Spotify_BIFV.pbix) · [Power BI template](powerbi/Spotify_BIFV.pbit)

## Project overview

- **Objective:** Explore how music popularity varies across genres, artists, release periods, and audio features.
- **Dataset:** 11,762 analyzed tracks (from a larger source dataset).
- **Data preparation:** Excel cleaning and an ETL notebook.
- **Data model:** Star schema with one fact table (`FactTracks`) and four dimensions (`DimGenre`, `DimArtist`, `DimTrack`, `DimDate`).
- **Reporting:** Three-page Power BI dashboard with DAX measures, trend analysis, and artist drill-through.
- **Collaboration:** Team project; team members worked together across project stages.

## Dashboard pages

1. **Executive summary** — overview of music popularity and key performance indicators.
2. **Audio feature analysis** — relationships between popularity and characteristics such as danceability and energy.
3. **Artist drill-through** — artist-level exploration and comparisons.

## Selected findings

- The dataset showed increasing popularity trends across releases from 2015–2020.
- Pop genres represented a substantial share of the analyzed tracks.
- Danceability and energy were positively **associated** with popularity in the analysis; these are not causal findings.
- Findings informed recommendations for playlist curation and artist promotion.

## Repository contents

| Path | Purpose |
| --- | --- |
| [`notebooks/etl_preprocessing.ipynb`](notebooks/etl_preprocessing.ipynb) | Original ETL and preprocessing notebook |
| `data/` | Cleaned analysis dataset and data dictionary (to be added) |
| [`powerbi/`](powerbi/) | [Power BI report](powerbi/Spotify_BIFV.pbix), [template](powerbi/Spotify_BIFV.pbit), and [dashboard preview](powerbi/dashboard_preview.pdf) |
| [`docs/`](docs/) | [Final report](docs/final_report.pdf), [data model diagram](docs/data_model_diagram.pdf), [DAX measures](docs/dax_measures.pdf), [use case](docs/use_case.pdf), and [presentation](docs/presentation.pdf) |

**Status:** Dashboard, ETL notebook, and supporting documentation available. Cleaned dataset and data dictionary are being added.


## Tools and techniques

**SQL**, dimensional modeling/star schema, **Power BI**, **DAX**, **Excel**, data cleaning, exploratory analysis, and data visualization.

## Limitations

The findings describe patterns in the analyzed Spotify dataset; correlations between audio features and popularity do not establish causation.
