**Dataset:**

### **reviews.json** file - Contains individual podcast reviews, each with fields

***podcast_id***: Identifier linking the review to a specific podcast.

***title***: Title of the review.

***content***: Full text of the review.

***rating***: Numerical rating provided by the reviewer.

***author_id***: Identifier for the review's author.

***created_at***: Timestamp indicating when the review was posted.​

### **Podcasts.json** file : this file contains metadata for each podcast

***podcast_id***: Unique identifier for the podcast.

***itunes_id***: Identifier from the iTunes platform.

***slug***: URL-friendly identifier for the podcast.

***itunes_url***: Direct link to the podcast on iTunes.

***title***: Title of the podcast.

***author***: Creator or host of the podcast.

***description***: Brief summary or overview of the podcast.

***average_rating***: Average user rating.

***ratings_count***: Total number of ratings received.

***scraped_at***: Timestamp indicating when the data was collected.​

### **categories.json** file: Maps podcasts to their respective categories, containing:

***podcast_id***: Identifier linking to the podcast.

***itunes_id***: iTunes-specific identifier.

***category***: Category or genre of the podcast
