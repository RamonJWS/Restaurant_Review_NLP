<h1 align='center'> Yelp_Review_NLP </h1>

## Project Motivation

In the modern day, public discussion and critiquing of products and services occurs beyond dedicated mediums, and now also takes place in the realm of social media.

What if a potential customer has already decided that they don’t want to visit a restaurant because of a friend’s tweet or Facebook review? 

Online restaurant reviews are currently found on Yelp, TripAdvisor, and Google Reviews. A new customer might find which restaurant they want to go to by browsing any one of these review sites. Opinions are shared constantly on social media platforms and are read by their followers. The knowledge of what these followers think about local restaurants, from reading these online posts, could help us better understand the general public's perception of certain restaurants.

By using NLP, on existing restaurant reviews from Yelp, I have created a model that can predict if the authors public message on social media is positive or negative.

## Data Source

Used data from Kaggle: https://www.kaggle.com/omkarsabnis/yelp-reviews-dataset

## Approach

The data was imbalanced with the majority of the data being positive reviews. To prevent bias in the model I used SMOTE to synthesize more negative reviews, thus balancing the data classes. I compared the performance of three machine learning algorithms (Naive Bayes Multinomial, Logistic Regression, and Random Forests) and found that the logistic regression gave the highest overall accuracy.

## Results

Using a tuned Logistic Regression, I managed to predict if social media posts about restaurants were negative or positive to a 89% accuracy.
