# Data Contest 2022
Predict hotel survey experience and ratings

### Description
Welcome to the PRML Nov-2022 data contest.
Here you will build prediction models for Customers to predict rating-scores that they will likely assign to hotel bookings. You can use all the extra information provided, such as customer's info, his/her demographic details, past experience ratings, hotel offering and other relevant descriptions.
This dataset is derived from a real world scenario; so take care of sanitizing/handling real data.

Use the data in creative ways to come up a ML model that predicts customer's score among different hotel bookings. Supervised data is available about earlier preferences in train.csv.

### Evaluation
Submissions are evaluated according to the Mean Squared Error (MSE), elaborate calculation below:

MSE is the squarred average squared differences between predicted value and the real value.
Lower the MSE, better the prediction.
MSE


### Submission Format
Your submissions should follow the format of sample_submission.csv file.
Each row in submission file should contain booking_id and rating_score.
Rating scores should be between 1-5

The file should contain a header and have the following format:

```
booking_id,rating_score 
4f3dcd52e63db7d045f64ff87188034c,1
b8cdd7b83e35a4243d81f7997e11582e,2
b47392f4a3685d56bada1341cb83bbf1,3
21cc23017f1c007a6712b2964eb001b5,4
f006b9b9440d1aa37d89c89446d2d651,5
```

### Citation
harishgp, PKKumar765, Prithaj Banerjee cs21s045, RahulVashisht. (2022). Data Contest 2022. Kaggle. https://kaggle.com/competitions/datacon-22

#### Kaggle Competition [Link](https://www.kaggle.com/competitions/datacon-22/overview)