# Recommendations with IBM
For this project we will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles we think they will like.

### File Description
    - data
    |- articles_community.csv  # data to process 
    |- user-item-interactions.csv  # data to process

    - project_tests.py  # test code 
    - Recommendations_with_IBM.ipynb  # notebook for development work
    - top_5.p
    - top_10.p
    - top_20.p
    - user_item_matrix.p

    - README.md

### Installation:
Run with Python 3 with libraries of numpy, pandas, matplotlib and pickle libraries.

### Project description:
Project is divided into the following tasks:

1. #### Exploratory Data Analysis: 
Before making recommendations, I am exploring the data which is required for the project.

2. #### Rank Based Recommendations:
To get started in building recommendations, I first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users.

3. #### User-User Based Collaborative Filtering:
In order to build better recommendations for the users of IBM's platform, I looked at users that are similar in terms of the items they have interacted with. These items are then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

4. #### Matrix Factorization:
Finally, I completed a machine learning approach to building recommendations. Using the user-item interactions, I build out a matrix decomposition. Using the decomposition, I got an idea of how well I can predict new articles an individual might interact with.

### Licensing, Author and Acknowledgement:
Thanks to [IBM](https://dataplatform.cloud.ibm.com/) for providing the data for Udacity program for training purpose. Code is saved in [GitHub](https://github.com/Riteshjj98/Recommendation-Engine)
