# Recommendation-Systems
We have always wondered how Amazon, Flipkart or even youtube suggest alternatives. The secret is the uses data to verify similarities. The recommender system is similarity-based modelling techniques which verify the association of data points and baskets preferences based on the same

Recommender system creates a matching between users and items and exploits the similarity between users/itemsto make recommendations. Proprietary content. ©Great Learning. All Rights Reserved. Unauthorized  use or distribution  prohibited
work flow of Project
# Data Set from  Amazon Reviews data: http://jmcauley.ucsd.edu/data/amazon/
  1  Importing Required Libraries
  2  Read and explore the dataset. ( Rename column, plot histograms, find data characteristics)
  3 Exploratory Data Analysis
  4 Statistical Analysis
  5 Model Preparation
     Data model preparation as per requirement on number of minimum ratings
  6 Split the data randomly into train and test dataset
  7 ## Build Popularity Recommender model.
  8 Sort the products on recommendation score
  9 Generate a recommendation rank based upon score 
  10 Use popularity based recommender model to make predictions.
  output- Since this is a popularity-based recommender model, recommendations remain the same for all users
   We predict the products based on the popularity. It is not personalized to particular user

   ## Hence, we are trying to Build Collaborative Filtering model
   Model-based Collaborative Filtering: Singular Value Decomposition.
   Here we are using SVD method- SVD is best to apply on a large sparse matrix.
   SVD is useful in many tasks, such as data compression, noise reduction similar to Principal Component Analysis and Latent Semantic Indexing (LSI), used in document retrieval and word similarity in Text mining
   repeating the same process by Builting the model and Testing. 

###OUTPUT SUMMARY
Model-based Collaborative Filtering is a personalised recommender system, the recommendations are based on the past behavior of the user and it is not dependent on any additional information.

The Popularity-based recommender system is non-personalised and the recommendations are based on frequecy counts, which may be not suitable to the user.You can see the differance above for the user id 121 & 200, The Popularity based model has recommended the same set of 5 products to both but Collaborative Filtering based model has recommended entire different list based on the user past purchase history
