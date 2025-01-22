# Sentiment Analysis on Amazon Alexa Reviews


This project performs sentiment analysis on customer reviews of Amazon Alexa products to classify them as positive or negative. The analysis involves data preprocessing, exploratory data analysis (EDA), and building machine learning models to predict sentiment based on customer feedback.

# Features
Data Preprocessing

Cleaned the dataset, handled null values, and created new features (e.g., review length).
Preprocessed text reviews with stemming and stopword removal.
Exploratory Data Analysis

Visualized the distribution of ratings, feedback, and product variations.
Generated word clouds for positive and negative sentiments.
Feature Engineering

Used CountVectorizer to convert textual reviews into numerical data (Bag of Words).
# Machine Learning Models

Implemented and compared multiple classification models:
Random Forest Classifier
XGBoost Classifier
Decision Tree Classifier
Performed cross-validation and hyperparameter tuning for optimal performance.
# Model Persistence

Saved key models and preprocessing tools (e.g., CountVectorizer, scalers, classifiers) for deployment.
# Dataset
The dataset contains Amazon Alexa customer reviews with the following key columns:

verified_reviews: Textual reviews provided by customers.
rating: Customer ratings on a scale of 1-5.
feedback: Sentiment labels (1 for positive, 0 for negative).
variation: Product variation (e.g., color, size).
Visual Insights
Rating Distribution: Most reviews have high ratings (4 or 5 stars).
Sentiment Breakdown: Around 91.87% of reviews are positive, while 8.13% are negative.
Word Clouds: Positive words (e.g., "good", "amazing") and negative words (e.g., "poor", "garbage") are prominently displayed.
# Model Performance
Model	Training Accuracy	Testing Accuracy
Random Forest	98%	91%
XGBoost	97%	92%
Decision Tree	95%	89%
Confusion matrices and evaluation metrics are visualized in the notebook for detailed performance analysis.



# Future Improvements
Use advanced NLP techniques like word embeddings (e.g., Word2Vec or GloVe).
Experiment with deep learning models like LSTMs or Transformers (BERT).
Deploy the trained model as a web application using Flask or FastAPI.

# License
This project is licensed under the MIT License.


