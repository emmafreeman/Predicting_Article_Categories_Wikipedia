# Predicting Wikipedia Article Categories 

For this project, I:

  * Wrote a series of Python scripts that used the Wikipedia API to get about 5,000 articles from 8 categories
  * Stored the articles in a Mongo database
  * Cleaned the article text using Pandas and RegEx
  * Used Natural Language Processing techniques / Latent Semantic Analysis (Tfidf and SVD) to create a semantic search engine, where you can input a search term and get a category that is the closest to that term, based on cosine similarities of the article vectors and the NearestNeighbors algorithm
  
