# player-replacement-case-study
Data-driven player replacement case study based on behavioural similarity

# Replacing a Player vs Replacing a Role

This repository contains a reproducible case study on player replacement in football,
focusing on behavioural similarity rather than season-level output.

## Project overview
The goal of this project is to show why players with similar headline statistics
often perform different roles on the pitch, and how data can help narrow down
replacement profiles more effectively.

The analysis is based on:
- match-level aggregated event data,
- behavioural feature engineering,
- cosine similarity and euclidean distance,
- PCA used as an interpretation tool.

## Contents
- `data/` – raw and processed datasets - players_data_2024_2025.csv its the right one
- `notebooks/` – full analysis in a Jupyter Notebook - similarity.ipynb its the right one
- `figures/` – visual outputs used in the article

## How to reproduce
1. Clone the repository
2. Install requirements
3. Run the notebook in `notebooks/`

## Disclaimer
This project uses publicly available data and is intended for educational
and analytical purposes only.
