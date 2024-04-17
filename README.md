# ML-Project-Yelp-Rating-Regression-Predictor

## Summary:

The main goal of the project is to use a multiple linear regression model to analyse which factors have the greatest impact on a restaurant's Yelp rating. To achieve this,  a dataset provided by Yelp will be used, which includes several JSON files with detailed information about businesses, reviews, users, check-in record, tips and photos. In this project, I will first scan and clean the data to make sure it is ready for analysis. Then, I will use multiple linear regression techniques to identify which restaurant characteristics have the greatest impact on their Yelp rating. Once I've tuned the model, I'll use it to predict the Yelp rating for a restaurant based on its specific characteristics.

## Content:

- `yelp_business.json`: Contains establishment data on the location and attributes of all businesses in the dataset. This includes information such as business category, opening hours, type of food, etc.
  
- `yelp_review.json`: Provides Yelp review metadata by business. This file includes information about the date of the review, the text of the review, the rating of the review, etc.

- `yelp_user.json`: Contains metadata of the user profile per business. Includes information on the number of reviews the user has made, the date of registration, the number of friends, etc.

- `yelp_checkin.json`: Provides online check-in metadata by business. This file includes information on the number of check-ins made on each day of the week at a specific business.

- `yelp_tip.json`: Provides metadata of tips by business. Includes information about the text of the tip, the date of the tip and the number of likes received.

- `yelp_photo.json`: Contains photo metadata by business. Includes information about the URL of the photo, the date of the photo, the number of likes received, etc.

- `yelp_regression.ipynb`: The notebook has explanations of the processes, analysis of the results, justifications of the decisions using tables and graphs.

## Technologies:

  - Python: data collection, data exploration and preprocessing, data visualization anda data partitioning.
  - Scikit-learn: model selection, model training, model evaluation, model tuning and model deployment.

## Author:
  
  - Arianna Potente Vázquez: https://github.com/Ari-Potente
