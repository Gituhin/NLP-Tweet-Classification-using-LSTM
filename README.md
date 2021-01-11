# NLP-Tweet-Classification-using-LSTM
Classifying tweets(bunch of statements) into disastrous or not
It's a binary classification. I am using LSTM to recognize some trend and pattern.
But the performance is not upto the mark since I am getting an accuracy upto 78% on validation set.

**Data Description:**
What should I expect the data format to be?
Each sample in the train and test set has the following information:

**The text of a tweet**
A keyword from that tweet (although this may be blank!)
The location the tweet was sent from (may also be blank)

**What am I predicting?**
You are predicting whether a given tweet is about a real disaster or not. If so, predict a 1. If not, predict a 0.

**Columns**
id - a unique identifier for each tweet
text - the text of the tweet
location - the location the tweet was sent from (may be blank)
keyword - a particular keyword from the tweet (may be blank)
target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)
