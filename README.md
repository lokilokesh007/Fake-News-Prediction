# Fake-News-Prediction

Background :
Social media has brought humanity together in new and innovative ways, but it has also given rise to fake news across various sectors, from politics to commerce. Detecting fake news 
is crucial because it can misinform individuals and communities, leading them to make decisions based on lies and deceit. One effective approach to identifying fake news is through 
machine learning.

Project Overview :
The Fake News Prediction project utilizes machine learning techniques and natural language processing (NLP) methods to identify and classify fake news articles. Here are the key 
components of the project:

Datasets :
id: Unique ID for a news article
title: The title of a news article
author: Author of the news article
text: The text of the article (could be incomplete)
label: A label that marks the article as potentially unreliable (1: unreliable, 0: reliable)

Data Cleaning: 
The data underwent several cleaning steps, including handling empty strings, creating binary labels (0 for fake, 1 for real), and combining title and text into a single 
column. Text preprocessing involved regex cleaning, stop word removal, and lemmatization.

Models:
Logistic Regression: A classification algorithm used to predict discrete classes (e.g., fake or real news).
Decision Tree: An alternative classification model.
