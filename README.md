# hotel-review-sentiment-analysis
This project analyses hotel reviews from TripAdvisor to determine whether the sentiment is positive or negative. It cleans and prepares the text data, then uses machine learning techniques to categorize the reviews. The best model is saved and can be used to predict sentiment for new reviews in the future.

## Details of data

The .csv file contains two columns, 'Review' and 'Rating'. 

## Key Features

- Text cleaning, tokenization, and stemming for data preprocessing.
- Trained models: Naive Bayes, SVC, Random Forest.
- Best model: Support Vector Classifier (SVC) with 90.22% accuracy via 5-fold cross-validation.
