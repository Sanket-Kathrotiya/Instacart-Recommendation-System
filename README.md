# Instacart-Recommendation-System
This repository contains the implementation of a recommendation system designed to provide product recommendations based on customer purchasing patterns from Instacart’s dataset. The system predicts which items a user is most likely to reorder in their next purchase, using a combination of machine learning techniques and data analysis.

### Data    
This data was retrieved from [Kaggle](https://www.kaggle.com/psparks/instacart-market-basket-analysis) and was provided by Instacart for a market basket analysis competition in 2018.  
<br/>
The data is divided into 6 files:  
<br/>
**Aisles.csv**: 134 Unique aisle numbers and descriptions  
**Departments.csv**: 21 Unique department numbers and descriptions  
**Products.csv**: 49,688 Unique product ids, with description, aisle id, and department id  
**Orders.csv**: 3,421,083 Unique order id, with user id, order number, order_dow, order_hour_of_day, days_since_prior_order, and eval_set indicating if the order is in train, prior, or test  
**Order_products__train.csv**: Order id, product id, add to cart order, and reorder indicator  
**Order_products__prior.csv**: Order id, product id, add to cart order, and reorder indicator  
  
## Project Notebooks

1. **[Clustering.ipynb](https://github.com/Sanket-Kathrotiya/Instacart-Recommendation-System/blob/main/Clustering.ipynb)**:  
   Clusters users using KMeans.

2. **[Recommendation_system.ipynb](https://github.com/Sanket-Kathrotiya/Instacart-Recommendation-System/blob/main/Recommendation_system.ipynb)**:  
   Implements a model-based recommendation system using SVD to predict product ratings and overcome popularity bias.

3. **[Recommendation_System_Re_Ranking.ipynb](https://github.com/Sanket-Kathrotiya/Instacart-Recommendation-System/blob/main/Recommendation_System_Re_Ranking.ipynb)**:  
   Generates association rules for frequently purchased items to enhance targeted marketing and product recommendations.


