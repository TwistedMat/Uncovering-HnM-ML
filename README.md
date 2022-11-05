# Uncovering-HnM-ML - Personalized Product Predictions in the Fast-Fashion Industry👗👖🛍️
## Can we use H&amp;M's data to understand latent pruchasing patterns and preferences of users and predict every user's next purchases?

## The WHY?
  * H&M spent just under ***$100 million on advertising*** in the past year with close to ***$25 million on just digital ads***.
  * Even though online sales increased since covid, this digital marketing spend was not able to be translated into sales with a ***21% drop in YoY sales*** in H&M’s first
quarter of 2021.

## The WHAT?
  * Using [H&Ms Kaggle dataset](https://www.kaggle.com/c/h-and-m-personalized-fashion-recommendations/overview), we have analyzed their purchases over a course of 2 years and attempted to create value for the Marketing Team using Machine Learning for targeted marketing. 

## The HOW? 
 * Prepared the data by Vectorizing Apparel Product Features and ***MICE (Multiple Imputation by Chained Equations)*** for imputation of User related Age feature. 
 * Utilized ML concept of ***K-means Clustering*** to identify specific groups of customers with high preference for specific product features and ***LDA for Topic Modeling*** to identify the hidden purchase patterns of users. 
 * Predicted Future User Purchases of H&M articles by understanding which sub-group a user belongs to and what product features are dominant in that group.  

## SO WHAT?
 * Our model output allows the marketing team to allocate their budget more efficiently and have better ***return-on-ads-spend*** by advertising the top predicted product for each segment to the customers in that group.
 * On the launch of a new product, based on the product features and segment preferences, H&M can do ***targeted marketing*** to the specific segment thereby decreasing their huge marketing spend.

Click here for the Video Walkthrough: [![Video Walkthrough](https://img.shields.io/badge/-Uncovering%20H%26M-red??style=social&logo=Youtube&link=https://www.youtube.com/watch?v=bljkNncvDOg)](https://www.youtube.com/watch?v=bljkNncvDOg)

Notebook best viewed in Google Collab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TwistedMat/Uncovering-HnM/blob/main/Uncovering_H&M_EDA_Project.ipynb)

