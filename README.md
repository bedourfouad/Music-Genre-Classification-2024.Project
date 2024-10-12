# Music Genre Classification 🎵

## Overview
This project aims to classify music tracks into different genres based on their characteristics. The dataset used for this project includes various musical features such as danceability, energy, and acousticness, sourced from a popular music platform.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Data Exploration](#data-exploration)
4. [Model Building](#model-building)
5. [Results](#results)
6. [Conclusion](#conclusion)

## Introduction
The dataset provides comprehensive information about various songs, where each row represents a song and its features. The goal is to analyze these features to understand their relationship with the song's genre and ultimately build a model to classify new tracks.

## Dataset
- **Features**:
  - `artist`: Name of the artist.
  - `song`: Name of the track.
  - `popularity`: Popularity score of the song.
  - `danceability`: Suitability for dancing.
  - `energy`: Measure of intensity and activity.
  - `key`: The musical key of the track.
  - `loudness`: Overall loudness in decibels.
  - `mode`: Modality of the track (major/minor).
  - `speechiness`: Presence of spoken words.
  - `acousticness`: Confidence that the track is acoustic.
  - `instrumentalness`: Predicts if the track contains no vocals.
  - `liveness`: Presence of an audience in the recording.
  - `valence`: Musical positiveness conveyed by the track.
  - `tempo`: Estimated tempo in beats per minute.
  - `duration`: Length of the track in milliseconds.
  - `time_signature`: Number of beats in each measure.
  - `Class`: Genre of the track.

## Data Exploration
The dataset was explored using visualizations to understand the distribution of different features, the relationships between them, and their impact on the genre classification. Key insights were drawn from various plots, including histograms, scatter plots, and heatmaps.

## Model Building
Several machine learning models were tested to classify the music genres. The models used include:
- XGBoost
- LightGBM
- Random Forest
- Logistic Regression
- CatBoost

The models were evaluated based on their performance metrics such as accuracy, precision, recall, and F1 score.

## Results
The performance of each model was compared, and the best-performing model was selected for further evaluation. The results demonstrate the effectiveness of the chosen model in classifying music genres based on their features.

## Conclusion
This project highlights the importance of various musical features in predicting the genre of a song. The findings can be useful for music recommendation systems and further research in the field of music analytics.

## Requirements
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- XGBoost
- LightGBM
- CatBoost
