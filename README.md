# YouTube Video Popularity Analysis

## Project Overview

This repository contains an exploratory analysis of YouTube video popularity using sample data for videos, channels, and comments. The analysis is organized into Jupyter notebooks covering data collection, natural language processing, network analysis, and virality modeling.

## Repository Structure

- `data_collection.ipynb` - Data preparation and exploratory analysis of the provided YouTube dataset.
- `nlp_analysis.ipynb` - Natural language processing of video titles, descriptions, and comments.
- `network_analysis.ipynb` - Analysis of network relationships and connectivity among channels, videos, and commenters.
- `virality_analysis.ipynb` - Analysis of viral patterns, popularity features, and modeling video success.
- `data/` - Sample input datasets.
  - `channels_sample.csv` - Channel-level metadata.
  - `comments_sample.csv` - Comment-level metadata and text.
  - `videos_sample.csv` - Video-level metadata and performance metrics.

## Data Description

The sample data includes key fields often used to model YouTube popularity, such as:

- Video metrics: views, likes, dislikes, comment counts, publication date.
- Channel attributes: subscriber count, channel title, category.
- Comments: comment text, author, like counts, timestamps.


### Prerequisites

- Python 3.8+ with Jupyter Notebook support
- Common data science packages such as: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `nltk`, `networkx`

### Recommended setup

1. Create a virtual environment:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

2. Install required packages:

```powershell
pip install pandas numpy matplotlib seaborn scikit-learn nltk networkx jupyter
```

3. Launch Jupyter Notebook:

```powershell
jupyter notebook
```

4. Open and run the notebooks in this repository.

## Notebook Guide

### `data_collection.ipynb`
- Loads the sample data files.
- Cleans and preprocesses tables.
- Performs exploratory data analysis (EDA) on video and channel features.
- Visualizes trends in view counts, likes, and category distributions.

### `nlp_analysis.ipynb`
- Tokenizes and analyzes text from titles, descriptions, and comments.
- Computes sentiment, word frequency, and topical signals.
- Examines how language features correlate with popularity.

### `network_analysis.ipynb`
- Builds graphs to explore relationships among videos, channels, and commenters.
- Measures connectivity, centrality, and community structure.
- Identifies network patterns related to popular content.

### `virality_analysis.ipynb`
- Investigates features that drive viral growth.
- Tests modeling approaches for predicting popularity.
- Explores triggers and key indicators of viral videos.

## Usage

Use this repository to:

- Learn how YouTube popularity can be analyzed with data science techniques.
- Prototype models that combine metadata, textual features, and network signals.
- Explore how sample video, channel, and comment data interact.

## Notes

- The repository does not include a production dataset or complete YouTube API pipeline.
- If you wish to extend the analysis, replace the sample CSVs with full datasets and update the notebooks accordingly.

