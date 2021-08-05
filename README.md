# Recommendations-with-IBM
![image1](https://github.com/blessokeke/Recommendations-with-IBM/blob/main/image/ibm.PNG)

## Project Overview
 In this project I will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles you think they will like. An example of the IBM Watson Platform dashboard with recommended articles is shown above.
 
 ## File Description
 This project has the following files:
 1. **Recommendations_with_IBM.ipynb:** This contains the analysis and implementation code.
 2. **Recommendations_with_IBM.html:** This contains the html file of `Recommendations_with_IBM.ipynb` file.
 3. **user-item-interactions.csv:** This is user-item interactions csv file found in the data folder.
 4. **articles_community.csv:** This is the indexed items csv file found in the data folder.

## Project Steps
This project is broken down into the following steps:
1. **Exploratory Data Analysis:** This step explores the data to get answers to the required questions needed to understand the data better. 
2. **Rank Based Recommendations:** In this step, I explored the most popular articles based on the most interactions. It is easy to assume that the articles with the most interactions are the most popular since there are no rating for any of the articles. These are then the articles we might recommend to new users (or anyone depending on what we know about them).
3. **User-User Based Collaborative Filtering:** Here I looked at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users and a step in the right direction towards a more personalized recommendations for the users.
4. **Matrix Factorization:** In this step, I completed the machine learning approach to building recommendations. I built a matrix decompositon using the user-item interactions. This gives an idea of how well one can predict new articles an individual might interact with.

 
 
### Acknowledgment
Many thanks to Udacity for giving me an opportunity to try out real world problems. Thanks to the Data Scientists who have inspired and provided insights to me through Github and StackOverflow.

This project was completed as part of the [Udacity Data Scientist Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025) program.

