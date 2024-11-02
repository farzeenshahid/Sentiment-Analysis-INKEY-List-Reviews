# Sentiment-Analysis-INKEY-List-Reviews
This repository contains a sentiment analysis project focused on product reviews for The INKEY List, a well-known skincare brand, using the Sephora dataset. The project explores customer sentiment to provide insights into overall brand perception and specific product feedback.
## Project Overview
This analysis aims to classify customer reviews of The INKEY List products into positive or negative sentiments using NLP techniques. The project includes data extraction, preprocessing, sentiment classification, and visualizations
## Methodology
+ **Data Preprocessing:** Text cleaning, tokenization, and removal of unnecessary columns.
+ **Modeling:**
  + **BERT Model:** A fine-tuned BERT model is used for sentiment classification.
  + **Zero-Shot Classification:** Reviews are classified as positive, negative, or neutral using a zero-shot approach, where a predefined prompt and labels (positive,       
    negative, neutral) help categorize reviews without additional model training.
  + **TF-IDF with Logistic Regression:** Reviews are vectorized using TfidfVectorizer, and a logistic regression model is trained for sentiment classification
+ **Evaluation:** Model performance is measured using metrics like accuracy, precision, recall, and F1-score.
+ **Visualization:** Word clouds and confusion matrices illustrate common terms and classification results.
## Results
The sentiment analysis provides a snapshot of customer satisfaction with The INKEY List products. Key findings include:

+ Distribution of positive, negative, and neutral sentiments.
+ Common words in each sentiment category visualized through word clouds.
+ Model performance metrics across different classification techniques.
