﻿# LightFM RecSys

## Collaborative Filtering Techniques
Nearest Neighbour Model: Use ratings of most similar users
Latent Factor Analysis: Solve for underlying factors that drive the ratings

## Cold-start problem
The challenge to recommend items to an entirely new user who has not interacted with any items yet.

## Hybrid recommender system
Can be used in case of cold-start problem, can recommend to both existing and new users.
Uses both collaborative and content based filtering for recommendations.

## Explicit Feedback: 
Ratings  and like/not like.

## Implicit Feedback: 
Clicks, watched movies, songs listened to etc.


## Evaluating the model
**AUC Score:** <br>
Measures ROC AUC metric for the model.
Probability  that a random chosen positive example has a higher score than a random chosen negative example. 

## Collaborative Filtering
*“People who agreed in the past will agree in the future.”* <br>
Based on what a user will like based on the similarity with other users. <br>
Person A likes items 1, 2, 3. <br>
Person B likes items 2, 3, 4. <br>
A should like item 4 and B should like item 1.


## Content Based Filtering
*“If you like an item you will also like a ‘similar’ item.”* <br>
Recommend products which are similar to the ones that a user has liked in the past. 
