
# Sentimental-Analysis
Sentiment Analysis is the process of determining whether a piece of writing is positive, negative or neutral.  
A sentiment analysis system for text analysis combines natural language processing (NLP) and machine learning techniques to assign weighted sentiment scores to the entities, topics, themes and categories within a sentence or phrase.  
Sentiment analysis helps data analysts within large enterprises gauge public opinion, conduct nuanced market research, monitor brand and product reputation, and understand customer experiences.
![image](https://user-images.githubusercontent.com/64374151/133586680-47385916-daa4-4a92-8ae6-70cdf4814478.png)

## How Does Sentiment Analysis Work?
Sentiment analysis, otherwise known as opinion mining, works thanks to natural language processing (NLP) and machine learning algorithms, to automatically determine the emotional tone behind online conversations.

There are different algorithms you can implement in sentiment analysis models, depending on how much data you need to analyze, and how accurate you need your model to be.

![image](https://user-images.githubusercontent.com/64374151/133587025-0bb23263-33bc-453e-8ed5-b609453484d6.png)

### The Training and Prediction Processes

In the training process (a), our model learns to associate a particular input (i.e., a text) to the corresponding output (tag) based on the test samples used for training. The feature extractor transfers the text input into a feature vector. Pairs of feature vectors and tags (e.g., positive, negative, or neutral) are fed into the machine learning algorithm to generate a model.

In the prediction process (b), the feature extractor is used to transform unseen text inputs into feature vectors. These feature vectors are then fed into the model, which generates predicted tags (again, positive, negative, or neutral).

### Feature Extraction from Text

The first step in a machine learning text classifier is to transform the text extraction or text vectorization, and the classical approach has been bag-of-words or bag-of-n grams with their frequency.

More recently, new feature extraction techniques have been applied based on word embeddings (also known as word vectors). This kind of representations makes it possible for words with similar meaning to have a similar representation, which can improve the performance of classifiers.

## Block Diagram
![image](https://user-images.githubusercontent.com/64374151/133587315-917899e6-4a22-474a-ac99-2d617c6536a6.png)

