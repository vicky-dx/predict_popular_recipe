# Recipe Traffic Prediction
This project aims to predict high traffic recipes for Tasty Bytes, a meal planning and recipe subscription service. By predicting which recipes will generate high traffic, Tasty Bytes can increase website traffic and subscriptions.

# Overview
The project uses a dataset of recipe features, such as cuisine type, course type, and recipe rating, to train a Linear Support Vector Classifier model to predict whether a recipe will generate high traffic. The model achieved an accuracy of 81% on the test set, and the confusion matrix and classification report are available in the results folder.

# Business Goal
The business goal of this project is to predict high traffic recipes with an 80% accuracy rate. This will allow the Product Manager to confidently select popular recipes for the homepage, increasing website traffic and subscriptions.

# Key Findings
  - The Linear SVC model achieved an accuracy of 81% on the test set.
  - The precision and recall scores for both classes were above 0.7.
  - The most important features for predicting high traffic were recipe rating and cuisine type.
# Recommendations
  - Deploy the machine learning model into production as soon as possible to predict high traffic recipes.
  - Collect additional data, such as time to make, cost per serving, ingredients, site duration time, income links, and recipe combinations, to improve the accuracy of the model.
  - Consider using an ensemble of models or exploring other machine learning algorithms to improve the accuracy of the model.
# Future Work
  - Explore the use of natural language processing techniques to incorporate recipe text data.
  - Build a recommendation system for personalized recipe suggestions based on user preferences and previous searches.
  - Investigate the impact of different homepage layouts and visualizations on website traffic and subscriptions.
