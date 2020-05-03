# cuddly-robot
Improvements to predictions for Labs 22 (Social Media)

## Goal
Improve prediction of engagements for social media messaging.

## current process
- For a user, retrieve data from Twitter for a number of that user's tweets
- Extract the texts of these tweets, and use Basilica to generate a set of embeddings
- Use 
  - these embeddings, and day-of-week and minute-of-day, 
  - and an engagement score (e.g., likes) to fit a linear regression model
- Use this set of embeddings to predict, for proposed tweet texts, an engagement score

## Problems
Linear Regression, based on text, does not seem to predict very well

Make sure that, when using the model to predict, a minute and day are included

## Questions
How am I getting a score if I am not incuding the time dimension?

## Improvments
- Double check current prediction method
- Check effect of normalizing
 Figure out how to compensate for values skewed left

