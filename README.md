# COGS-109-UCSD-Final-Project
## Airbnb Analysis Project

## Title: On the relativity of star ratings and how to understand them depending on cultural and geographical groups
Contributors:<br />
Christopher Jensen (cajensen@ucsd.edu)<br />
Lana Andreasyan (landreas@ucsd.edu)<br />
Amine M’Charrak (amine.mcharrak@tum.de)<br />

## Q&A:

### Q1: Which dataset did we identify to study? <br />

Airbnb Dataset provided by Tom Slee.

### Q2: Why did you choose this topic and dataset? <br />

We all agreed, that we are heavily influenced by rating systems and often let ratings take over huge parts of our final decision. It goes so far that we even exclude possible candidates (accommodations) by simply relying on single scores (average rating value).

### Q3: What do you want to analyze in this dataset? <br />

We want to investigate the meaning of the star rating system. Is this ranking relevant to everyone, are the requirements for a five star rating always the same or are there depending on the cultural group surprising differences? Can we come up with a general and simplified model with less predictors and successfully apply it onto similar datasets for different locations?

### Q4: Where do you start and how do you proceed? <br />

Step one: We want to do an exploratory analysis of the dataset in order to identify interesting phenomena or significant associations between predictors and response. Step two: We would like to solve a predictive task by applying our own model on this dataset using predictors we found to be helpful in step one.

### Q5: Okay. So how are you going to do this and which methods are you going to apply? <br />

The challenge is, that we do not know the true relationship between predictors and response. Therefore, we will have to select the appropriate model by taking several aspects into account. We have to consider not only the size of our dataset but also prevent overfitting by choosing a not too complex model and thus we want to make use of cross validation. Next we want to apply multi-linear regression onto our dataset in order to identify which variables are significant for predicting the overall satisfaction which is denoted by the average rating in units of stars. Finally, we want to use principal component analysis (PCA) to reduce the dimensionality of our feature space but still make acceptable predictions but this time with a much simpler model.

### Q6: What outcome do you expect from your project and what decides whether you succeeded? <br />

We would be really happy if we are able to uncover counterintuitive trends and associations in our dataset and perhaps make out interesting relationships which disprove our common sense of how we make decisions based on rating systems. All in all, we want to gain a better understanding of the real value of this five star based rating hierarchy.
