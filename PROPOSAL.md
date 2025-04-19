# **Podcast Review Summarization and Sentiment Analysis**

I have selected Modeling experiment as my term project and this proposal gives a detailed information about the project I will be working on.

Podcast Review Summarization and Sentiment Analysis is an NLP task that involves analyzing reviews given by podcast listeners and extracting a summary out of it. Analyzing the reviews and with sentiment analysis, we can detect the emotional tone like positive, negative, or neutral from the feedback received. Combining these two tasks as a single project will help podcast creators and platforms like Apple Podcasts, Spotify to understand audience responses and make data driven improvements to content produced.

The dataset I will be using for the project is a kaggle dataset and you can find it here <https://www.kaggle.com/datasets/thoughtvector/podcastreviews/data?select=reviews.json>

​The Podcast Reviews dataset on Kaggle, curated by Thought Vector, comprises over 2 million user-generated reviews for approximately 100,000 podcasts, primarily sourced from Apple Podcasts. This dataset is structured across three JSON files:​

-   reviews.json – contains individual user reviews

-   podcasts.json – includes metadata about each podcast

-   categories.json – maps each podcast to its genre/category

For the initial development, I am planning to use a smaller part of this large dataset, as it is a huge data.

## Methodology:

### Data Collection & Preprocessing:

Load and clean reviews.json, podcasts.json, and categories.json. Remove null, non-English, or irrelevant text, and apply tokenization, stopword removal, and optional lemmatization.

### Exploratory Data Analysis (EDA):

EDA will help understand the data's structure and key patterns. We will analyze the distribution of ratings, review lengths, and identify the most-reviewed podcasts

### Text Summarization:

Summarize grouped reviews per podcast using two approaches:

-   Extractive (e.g., TextRank using Sumy/Gensim): extract key sentences.

-   Abstractive (e.g., T5, BART): generate human-like summaries. Summarization will be based on the top N longest or most recent reviews per podcast.

###  Sentiment Analysis:

Detect the sentiment of each review using:

-   **Rule-based model**: VADER (suitable for short texts)

-   **ML/DL model**: Fine-tuned BERT or DistilBERT (using HuggingFace pipeline)\
    Reviews will be labeled as Positive, Negative, or Neutral, and probability scores will be stored for analysis.

### Results:

Sentiment results will be aggregated by podcast, genre, and optionally over time to track trends. Insights will be paired with summaries to give a full picture of audience feedback. Visualizations will include word clouds, sentiment pie/bar charts by genre, and category based heatmaps.

### Evaluation:

-   **Summarization**: ROUGE scores (if ground truth available) or manual review for coherence and informativeness.

-   **Sentiment**: Use review ratings to create labeled data (1–2 = Negative, 3 = Neutral, 4–5 = Positive) and evaluate using Accuracy, Precision, Recall, F1-score, and confusion matrices.

Link to my github repo: <https://github.com/yashvikommidii/Podcast-Review-Summarization-and-Sentiment-Analysis/tree/main>

Unlike many existing projects that focus solely on sentiment analysis or summarization, this project combines both using real world podcast review data. It offers a complete pipeline from preprocessing to evaluation making it a comprehensive and practical resource for NLP applications
