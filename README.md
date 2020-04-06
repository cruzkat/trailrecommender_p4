# Trail Recommender System

AllTrails.com is a popular resource for hiking trails. While the site does have a search bar as well as a 'You Might Also Like' feature that shows similar trails on an individual trail page, my problem was that I was only finding hikes within one geographical area. Because I enjoy to travel and often travel to hike, I was interested in recommendations for similar hikes all over California. To answer this question, I scrape AllTrails.com for 1050 of California's top trails and created a recommender system to return similar trails based on a trail input.

This project contains 4 notebooks.

## 1. Webscraping
This notebook is where I scraped top trails, trail attributes, and user reviews from AllTrails.com and stored into dataframes.

## 2. Text Preprocessing
The Natural Language Processing takes place in this notebook. I performed text preprocessing by removing punctuation, stopwords, and lemmatization. Then I ran through multiple techniques for topic modeling.

## 3. Clustering
Once I had my final topics from the user reviews, I performed clustering to analyze the distribution of my topics across all documents (user reviews) in my corpus.

## 4. Trail Recommender
Finally, I used the topic groupings and a function for cosine similarity to create a recommender system. I was pleased with my results and have added new trails on my to-do list!