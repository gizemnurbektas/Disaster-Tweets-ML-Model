# Disaster Tweet Classification with Machine Learning

A Google Colab notebook for exploratory analysis and classical machine-learning classification of tweets as disaster-related or not disaster-related.

## Project workflow

- Inspect the dataset and class balance.
- Clean tweet text and explore word frequencies, n-grams, and word clouds.
- Compare CountVectorizer, TF-IDF, and combined text features.
- Train Logistic Regression, Multinomial Naive Bayes, Decision Tree, and Random Forest models; selected sections use GridSearchCV.
- Review accuracy and class-level precision, recall, and F1 metrics.

## Dataset

The notebook uses `tweets.csv`, which contains `text` and binary `target` labels (`0` = not disaster-related, `1` = disaster-related), as well as keyword and location fields. The CSV is included in this repository for convenient access.

The dataset is sourced from [Disaster Tweets by Viktor S on Kaggle](https://www.kaggle.com/datasets/vstepanenko/disaster-tweets), which lists it as **CC0 1.0 Public Domain**. It contains more than 11,000 tweets. The source notes that some text may be profane, vulgar, or offensive. Please consult the Kaggle page for provenance and dataset details.

## Run in Google Colab

1. Open `tweets.ipynb` in Google Colab.
2. Download `tweets.csv` from this repository and upload it when prompted by the notebook.
3. Run the cells in order and install any packages requested by the runtime.

The notebook contains evaluation code. Model results depend on the runtime, data split, and configuration; use the outputs from your own execution rather than assuming fixed benchmark scores.

## Repository contents

- `tweets.ipynb` — data exploration, text preprocessing, feature extraction, model training, and evaluation.
- `tweets.csv` — CC0 disaster tweet dataset; source and license are linked above.
- `README.md` — project overview and usage instructions.

## Author

Gizem Bektaş
