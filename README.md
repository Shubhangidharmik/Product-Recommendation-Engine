# Product Recommendation Engine

![Screenshot (217)](https://user-images.githubusercontent.com/85070726/161027610-631db98d-ae78-4ca8-bba6-d144a4acc0e7.png)

## Objectives - 
The main objective is to recommend a product for users which reviews customer ratings and purchase history to recommend items and improve sales. Recommender systems are really critical in some industries as they create a huge impact on income.

## Project files Decription
**1)Product_Recommendation_Engine_updated_Capstone_Project.ipynb** - Includes all functions required for recommendation based filtering operations.

**2)Popularity_based_on_product_and_rating.ipynb** - Include recommendation of item to the user with the help of popularity based filtering.

 ### Popularity Based Approach

It is a type of recommendation system which works on the principle of popularity and or anything which most of the user suggest. These systems recommend products which are in trend or are most popular amongst the users.

so if a product is purchased by many people then the system will get to know that that product is most popular so for every new user, the system will recommend that product to user. 
 

### Collaborative Filtering

Collaboratory filtering makes automatic prediction about interest of user by collecting preferences or taste info from many users. suggest the product to the user who has same characteristics so based on behavior it recommende the product to the user.
 
The similarity is not restricted to the taste of the user, moreover there can be consideration of similarity between different items.

There are the various types of collaboratory filtering

1. **Memory based** - uses memory of previous user interaction to compute similarities based on item the interacted. This filtering is easy to implement but not does well for many users like new user who is not interacted yet. 

2. **Model based** - in this approach models are developed using different machine learning algorithm to recommend item to user. Like neural network, clustering technique, latent factor model (SVD) singular value decomposition. Model-based recommendation systems build a model based on the ratings of product. We extract some information from the dataset, and use that to make recommendations without having to use the complete dataset every time.

