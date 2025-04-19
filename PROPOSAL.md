# **Podcast Review Summarization and Sentiment Analysis**

I have selected Modelling experiement as my term project and this proposal gives a detailed information about the project I will be working on.

Podcast Review Summarization and Sentiment Analysis is an NLP task that involves analyzing reviews given by podcast listeners and extracting a summary out of it. Analyzing the reviews and with sentiment analysis, we can detect the emotional tone like positive, negative, or neutral from the feedbacks received. Combining these two tasks as a single project will help podcast creators and platforms like apple podcasts, Spotify to understand audience responses and make data driven improvements to content produced.

The dataset I will be using for the project is a kaggle dataset and you can find it here <https://www.kaggle.com/datasets/thoughtvector/podcastreviews/data?select=reviews.json>

​The Podcast Reviews dataset on Kaggle, curated by Thought Vector, comprises over 2 million user-generated reviews for approximately 100,000 podcasts, primarily sourced from Apple Podcasts. This dataset is structured across three JSON files:​

### **reviews.json** file - Contains individual podcast reviews, each with fields

***podcast_id***: Identifier linking the review to a specific podcast.

***title***: Title of the review.

***content***: Full text of the review.

***rating***: Numerical rating provided by the reviewer.

***author_id***: Identifier for the review's author.

***created_at***: Timestamp indicating when the review was posted.​

### **Podcasts.json file : this file contains metadata for each podcast**

***podcast_id***: Unique identifier for the podcast.

***itunes_id***: Identifier from the iTunes platform.

***slug***: URL-friendly identifier for the podcast.

***itunes_url***: Direct link to the podcast on iTunes.

***title***: Title of the podcast.

***author***: Creator or host of the podcast.

***description***: Brief summary or overview of the podcast.

average_rating: Average user rating.

ratings_count: Total number of ratings received.

scraped_at: Timestamp indicating when the data was collected.​

### **categories.json file: Maps podcasts to their respective categories, containing:**

podcast_id: Identifier linking to the podcast.

itunes_id: iTunes-specific identifier.

category: Category or genre of the podcast
