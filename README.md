# Recommendation-System-Engine-for-Products-on-E-Commerce-Website
Machine Learning used to design system which recommend products to users based on various scenarios.

A data driven recommendation system can assist a business improve user  experience on website and result in better customer acquisition and retention.


## Documentation

The recommendation system, I have designed is based on the journey of a new customer from the time they lands on the business’s website for the first time to when they makes repeat purchases.

The recommendation system is designed in 3 parts based on the business context:
1. Recommendation system -A: Product pupularity based system targetted at new customers: Used product ratings.
2. Recommendation system -B: Model-based collaborative filtering system based on customer's purchase history and ratings provided by other users who bought items similar items.
3. Recommendation system -C: When a business is setting up its e-commerce website for the first time without any product rating.

 
When a new customer without any previous purchase history visits the e-commerce website for the first time, they are recommended the most popular products sold on the company's website. Once, they make a purchase, the recommendation system updates and recommends other products based on the purchase history and ratings provided by other users on the website. The latter part is done using collaborative filtering techniques.

 ## Overview
1.Recommendation System - A

Product popularity based recommendation system targeted at new customers.
It is a great strategy to target the new customers with the most popular products sold on a business's website and is very useful to cold start a recommendation engine.

2.Recommendation System - B

Model-based collaborative filtering system:
Recommend items to users based on purchase history and similarity of ratings provided by other users who bought items similar to that of a particular customer.

A model based collaborative filtering technique is chosen here as it helps in predicting products for a particular user by identifying patterns based on preferences from multiple user data.The concept of Singular Value Decomposition is used here.
It recommendes top 10 highly correlated products in sequence based on a customer's purchase history.

3.Recommendation System- C 
Solves cold start problem for new businesses: When a business is setting up its e-commerce website for the first time without any historical data on product rating.
For a business without any user-item purchase history, a search engine based recommendation system can be designed for users. The product recommendations can be based on textual clustering analysis given in product description.
Here top words in the first 3 clusters based on text analysis and clustering techniques applied to product description.

Recommendation Technique:
Once a cluster is identified based on the user's search words, the recommendation system can display items from the corresponding product clusters based on the product descriptions.

Summary:
This recommendation engine supports  multiple scenarios. From a business setting up its e-commerce website for the first time and does not have user-item purchase/rating history to start with initally. This recommendation system will help the users get a good recommendation to start with and once the buyers have a purchased history, the recommendation engine can use the model based collaborative filtering technique.



