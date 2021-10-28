![product-recommendations-hero](https://user-images.githubusercontent.com/79034119/139304863-9fbb390f-1743-4cc7-a893-810d5b02b44d.png)



We present a product recommender model that is based on collaborative filter-
ing. In this model, we have a 2 million customer review and ratings of beauty related
products sold on amazon. The results showed that our model can provide appropriate
recommendations to users.

## 1. Introduction:
Recommender model as one of the MOST demanding algorithms in recent times
mainly in product based companies. With growing customers and use of digital media,
recommender system helps to boost an app’s/websites engagement with its users. In
this project, we developed a recommender model by using dataset related to over 2
Million customer reviews and ratings of Beauty related products sold on Amazon’s
website.

## 2. Problem Statement :
We have dataset related to over 2 Million customer reviews and ratings of Beauty
related products sold on Amazon’s website, and we are to develop a product recom-
mender model using different approaches.

The Dataset has 4 columns:

• UserId: Unique code given to each users.

• ProductId: Unique code given to each product.

• Rating: On basis of experience, users rate product from 1 to 5.

• Timestamp: digital record of the time of occurrence of a particular event.

## 3. Methodology :

1. Installing libraries and getting Data
2. Check for null values and outliers
3. Exploratory Data Analysis
4. Model Preparation
5. Different Model approach and selection of best Model
6. Hyper parameter tuning of model
7. Final Evaluation.
8. Working

## 4.Approaches:

**1. Popularity based recommendation Model**: 

**2. Collaborative Filtering Recommendation Model**

   **2.1 KNN**

   **2.2 Matrix Factorization - Singular Value decomposition**




![download (5)](https://user-images.githubusercontent.com/79034119/139305617-22315c8e-d324-42ea-b246-6e198313c965.png)




## 5. Result:

While selection of model Popularity Model gave an RMSE of 1.3 whereas KNNwithMeans model gave 1.05 which was better than popularity based. Further using
SVD we got RMSE as 1.01 which was the lowest and on further hyper parameter tuning
we got RMSE as 0.87.
