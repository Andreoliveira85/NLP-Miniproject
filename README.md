# NLP-Miniproject

## Project description:

In this NLP project we will be attempting to classify Yelp Reviews into 1 star or 5 star categories based off the text content in the reviews.

Each observation in this dataset is a review of a particular business by a particular user.

The "stars" column is the number of stars (1 through 5) assigned by the reviewer to the business. (Higher stars is better.) In other words, it is the rating of the business by the person who wrote the review.

The "cool" column is the number of "cool" votes this review received from other Yelp users. 

All reviews start with 0 "cool" votes, and there is no limit to how many "cool" votes a review can receive. In other words, it is a rating of the review itself, not a rating of the business.

The "useful" and "funny" columns are similar to the "cool" column.

## Methodologies:

After bivariate visualization analysis we construct a ML Pipeline based on the vectorization of the text of the reviews and a Multinomial Naive Bayes model to predict probability of bad reviews (1 star) or good reviews (5 stars). The classification report is below:  
                precision    recall  f1-score   support

           1       0.91      0.68      0.78       228
           5       0.93      0.98      0.96       998

    accuracy                           0.93      1226
   macro avg       0.92      0.83      0.87      1226
weighted avg       0.93      0.93      0.92      1226

## Code and resources used:

**Python version:** 3.7
**Libraries/packages:** pandas, numpy, scikitlearn.
**Dataset:** available at the repo


