# Data Wrangling SOP with WeRateDogs website
# Data Wrangling Project with Udacity

## Introduction
This is a data wrangling project aiming at providing a standardized reference for my data wrangling procedure. I am aiming here to provide structure and enhancing code readability for my future efforts in data wrangling.

WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. As it might be obvious, because "they're good dogs." WeRateDogs has over 4 million followers and has received international media coverage.

WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively to be used in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017.

Tweepy package and tweeter API was used to collect the current status (retweet and favorite status) for the provided tweet IDs. At this stage, it is important to acknowledge that tweeter enabled me a developer account and provided me with needed keys to use tweeter APIs. A software was used to predict the dog breed in the tweets. The predictions were supplied in a separate data file.

In the previous data wrangling efforts, data were gathered, assessed, cleaned and finally combined in one master document to be used in data analysis and visualization.

This data analysis project will attempt to answer these questions:-

Does one class of DoggoLingo receive more ratings than the others?
Is dog class (DoggoLingo) „doggo, puppo... etc“ is associated with higher retweets and favourites?
Is there a specific breed that has more retweets and favourite records than the others?
Is there a relationship between ratings, favourite counts and retweets?

## Language and Package
Python, pandas
