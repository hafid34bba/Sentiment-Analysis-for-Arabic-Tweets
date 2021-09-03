# Sentiment-Analysis-for-Arabic-Tweets

Natural Language Processing (NLP) is a hotbed of research in data science these days and one of the most common applications of NLP is sentiment analysis. From opinion polls to creating entire marketing strategies, this domain has completely reshaped the way businesses work, which is why this is an area every data scientist must be familiar with.

# Data
The data used for that project was collected from Twitter.

# Tweets length:
![](tweets_size.png)

# WordsCloud for positive Tweets 

![](positive_words.png)

# WordsCloud for negative Tweets 

![](neg_words.png)

# Data Cleaning 

- Remove punctuation<br>
- Remove special characters and patterns
- Remove emojis 
# Extracting Features from Cleaned Tweets
- Bag of Words
- TF-IDF
# Word Embeddings
 1. Word2Vec
 2. Doc2Vec 
# Classification models

1. Logistic Regression
2. Support Vector Machine
3. Random Forest
4. XGBoost

# Results

# 1. Logistic Regression

| Feature         | f1 score       |
| --------------- | -------------- |
| Bag of Words    | 0.628          |  
| TF-IDF          | 0.621          |
| Word2Vec        | 0.6            |
| Doc2Vec         | 0.54           |

# 2. SVM
| Feature         | f1 score       |
| --------------- | -------------- |
| Bag of Words    | 0.615          |  
| TF-IDF          | 0.615          |
| Word2Vec        | 0.6            |
| Doc2Vec         | 0.55           |

# 3. Random Forest
| Feature         | f1 score       |
| --------------- | -------------- |
| Bag of Words    | 0.576          |  
| TF-IDF          | 0.568          |
| Word2Vec        | 0.526          |
| Doc2Vec         | 0.41           |

# 4. XGBoost
| Feature         | f1 score       |
| --------------- | -------------- |
| Bag of Words    | 0.576          |  
| TF-IDF          | 0.581          |
| Word2Vec        | 0.598          |
| Doc2Vec         | 0.5            |

