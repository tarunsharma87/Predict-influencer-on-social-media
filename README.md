# Predict-influencer-on-social-media

## About the Dataset
The dataset, provided by Peerindex, comprises a standard, pair-wise preference learning task. Each datapoint describes two individuals. Pre-computed, standardised features based on twitter activity (such as volume of interactions, number of followers, etc) is provided for each individual.

The discrete label represents a human judgement about which one of the two individuals is more influential. The goal of the challenge is to train a machine learning model which, for a pair of individuals, predicts the human judgement on who is more influential with high accuracy. Labels for the dataset have been collected by PeerIndex using an application similar to the one described in this post.

## My Approch
Firstly I did EDA to get insights about the dataset. By doing EDA i got to know that, dataset follows a Exponential distribution. Then classified the dataset by describing the difference between similar attributes and at the end, have used LGBM to classify and predict the choice score. Submission for this problem is saved into `sub.csv` file
