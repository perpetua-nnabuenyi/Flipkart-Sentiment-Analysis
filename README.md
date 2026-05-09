# Flipkart Sentiment Analysis: Addressing Class Imbalance in Consumer Feedback
This project implements a machine learning pipeline to classify customer sentiment from Flipkart product reviews.
Key Technical Highlights:
Handling Imbalance: Addressed a significant 81% positive class skew by implementing balanced class weights in Random Forest and Logistic Regression models.
Feature Engineering: Utilized TfidfVectorizer for text representation and WordClouds for qualitative exploratory data analysis (EDA).
Optimization: Refined model selection to prioritize recall for neutral and negative sentiments, ensuring critical feedback is not overlooked.
Tools: Python (Scikit-Learn, Pandas), NLP (Tfidf), Visualization (Matplotlib, Seaborn).
