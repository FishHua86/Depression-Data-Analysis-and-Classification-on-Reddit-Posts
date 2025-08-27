# Depression Data Analysis and Classification on Reddit Posts

## Project Overview

This repository contains data and analysis notebooks for exploring depression-related content on Reddit. 

This project aims to analyse social media text data related to depression and explore methods for early detection.

The project focuses on text analysis, visualisation, topic modelling, and classification modelling.

## Data

The dataset used in this project is a public available dataset sourced from Kaggle. It includes over 7000 posts from Reddit. All post text were manually labelled as “depressed” or “non-depressed”. The data was originally posted by Reddit users in communities about mental health and daily life. The dataset contains two columns: one with cleaned post text, and the other with classification labels.

## Project Structure

```
depression_data_analysis/
│
├── data/
│   ├── README.md         # Description of datasets
│   └── reddit_depression.csv  # Main dataset
│
├── notebooks/
│   ├── 1_main_analysis.ipynb  # Main analysis notebook
│   ├── lda_vis.html            # LDA topic visualization
│   ├── lda_vis_depressed.html  # LDA topics for depressed users
│   └── lda_vis_non_depressed.html  # LDA topics for non-depressed users
│
├── README.md
└── requirements.txt  # Python package requirements
```

## Description

- **data/**: Contains the dataset and a README describing the data source and features.
- **notebooks/**: Jupyter notebooks and generated visualizations for text and topic analysis.
- **requirements.txt**: Lists the Python libraries needed to run the notebooks.

## How to Run

1. Clone this repository:

   ```
   git clone https://github.com/FishHua86/Depression-Data-Analysis-and-Classification-on-Reddit-Posts.git
   ```

2. Install required packages:

   ```
   pip install -r requirements.txt
   ```

3. Open and run the notebooks in `notebooks/` to explore the analysis.

## Notes

- The analysis focuses on Reddit posts related to mental health and depression.
- The LDA interactive visualizations (`lda_vis.html`, `lda_vis_depressed.html`, `lda_vis_non_depressed.html`) allow you to explore topics from the text data. Open any HTML file in a browser, hover over a topic to see its top words, and click on a topic to view the distribution of posts across that topic.
- Contributions are welcome to improve analysis methods, add models, or extend the dataset.

