# Food Review Rating Prediction

The data used in this project is taken from https://www.kaggle.com/snap/amazon-fine-food-reviews and consists reviews of food from Amazon. 
The data has a 'Score' column, starting from 1 to 5 and 5 being the very positive review.
When we looked at the data we noticed that positive reviews tend to have more '!' (exclamation points) in them.
Our hypothesis is that if a review has more '!' in it, it has a higher rating. Our prediction will be based on this.

The initial hypothesis testing shows that:

In reviews with a score 5; in every 2.37,
in score 4; in every 5.66, 
in score 3; in every 11.84, 
in score 2; in every 7.68, 
in score 1; in every 2.88 comment there is one comment that involves an !

