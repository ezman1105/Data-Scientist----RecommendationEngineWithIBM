
# Project -- Recommendations with IBM
Udacity Data Scientist Nanodegree - Recommendation with IBM

## Motivation

Being recommended by various types of products or services when we browse on the social media or just would like to reserve a room in Airbnb becomes an usual scenario as a part of surfing the Internet. While sometimes it's annoying when advertisments are frequently jumping out, it's also provide users novelty and serendipity when the recommendations spot on their requests. The mechanism behind the recommendation engines is explored, and the interactions between users and articles is also analyzed in this project.


## Libraries

1. Python3
2. Numpy
3. Pandas
4. Pickle

Please refer to 'requirement.txt' for details

## File Discription

1. data/**user-item-interactions.csv** -> Dataframe includes includes information of article id, title of article, and email
2. data/**articles_community.csv** --> Dataframe includes contains columns such as id, descriptions, status, full name of articles
3. **Recommendations_with_IBM.ipynb** --> Jupyter notebook containing main implementation and analysis

Supporting documents
1. **project_test.py** --> Verification of solutions in Jupyter notebook
2. **top_5.p** --> Verification of solutions in Jupyter notebook
3. **top_10.p** --> Verification of solutions in Jupyter notebook
4. **top_20.p** --> Verification of solutions in Jupyter notebook

## Content

I. Exploratory Data Analysis
II. Rank Based Recommendations
III. User-User Based Collaborative Filtering
IV. Content Based Recommendations (EXTRA - NOT REQUIRED)
V. Matrix Factorization

## Conclusion

An obvious trend can be observed that the accuracy related to the training data tends to increase when the latent features rises. On the other hand, the accuracy associated with the test data reveals the opposite movement. The difference would be due to the lack of users shared in training and testing data, since only 20 users are found in the test data, which would be insufficient to lead a solid result of estimation to actual values.

It's hard to jump into conclusion that SVD is a reliable recommendation engine in this project. Clearly, the dataset is quite limited. Compared to rating-type system, binary oriented (with 1s and 0s) dataset is more likely to demonstrate imbalanced interactions among users and items (such as articles in this case). Additional recommendation agorithems could be applied. Moreover, since matrix factorization is an offline verification method to evaluate the performance of the prediction model, online testing (such as A/B testing) would be conducted as a possible solution to the issue of limited users in the dataset.

## Licensing and Acknowledgements
1. The datasets are shared by Udacity from IBM

## Screenshots

<Screenshot> Distribution of Articles & Users
![image](https://github.com/ezman1105/Data-Scientist----RecommendationsWithIBM/blob/471fcd555d1a476ee80ac97a53844a3a8468d59b/Images/Distribution%20of%20Article%20%26%20user.png)

<Screenshot> Accuracy vs. Number of Latent Features
![image](https://github.com/ezman1105/Data-Scientist----RecommendationsWithIBM/blob/471fcd555d1a476ee80ac97a53844a3a8468d59b/Images/Accuracy%20vs.%20Number%20of%20Latent%20Features.png)


