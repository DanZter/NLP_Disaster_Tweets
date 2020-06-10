# NLP_Disaster_Tweets
Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

But, it’s not always clear whether a person’s words are actually announcing a disaster. Take this example:

"LOOK AT THE SKY LAST NIGHT IT WAS ABLAZE"

The author explicitly uses the word “ABLAZE” but means it metaphorically. This is clear to a human right away, especially with the visual aid. But it’s less clear to a machine.

# AIM:

Building a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. Using a dataset of 10,000 tweets.

# DATA
### Files
train.csv - the training set

test.csv - the test set

sample_submission.csv - a sample submission file in the correct format

### Columns
id - a unique identifier for each tweet

text - the text of the tweet

location - the location the tweet was sent from (may be blank)

keyword - a particular keyword from the tweet (may be blank)

target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)
