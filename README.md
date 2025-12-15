# NFL Game Outcome Predictor

Built an end-to-end machine learning pipeline to predict NFL game outcomes using historical play-by-play data.

## Overview
- Aggregated raw NFL play-by-play data into game-level records
- Engineered temporal and matchup-based performance features
- Handled missing data using imputation pipelines
- Trained interpretable classification models and evaluated performance using accuracy, recall, and ROC-AUC

## Results
- Accuracy: ~57%
- Balanced recall across home and away outcomes
- ROC-AUC: ~0.60

## Tech Stack
Python, Pandas, scikit-learn

## Notes
This project prioritizes clean data handling and leakage-free evaluation over maximizing accuracy.
