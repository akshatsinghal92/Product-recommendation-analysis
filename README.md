# Product-recommendation-analysis

## Business problem:
- If any pdt is purchased on the client website, it receives a rating and reviews based on its taste, price, etc.
- Based on these factors, the product may or may not be recommended further.
- But sometimes, the recommendation details about a product are missing on the webpage. It is difficult for the customer to categorize it as a good or a bad product just based on ratings and reviews. 
- So, the main problem is to investigate the possible reason for the missing recommendation details and find a way to predict the recommendation details for such products.

## Techniques involved:
- Web extraction using selenium
- Data analytics and visualisations on extracted dataset using seaborn plots
- Sentiment analysis on product reviews using textblob
- Word embeddings generation from reviews using Universal sentence encoder(transformer)
- Regression modelling with Rnadom forest, Xgboost, Lasso regressor models
- Interpretation and comparison of models using PDP plots, Q-Q and histogram plots of residuals

## Conclusion:
- Based on the reviews, ratings of various users for different products, this model predicts recommendation score which gives even more clear picture compared to manual recommendation feedback given by customers.
- As recommendation score for some products is very low, we can analyze the number of sales & revenue for these products.
- Based on that, we  can decide whether to spend resources on those or, should we concentrate on other revenue generating products.
- Also, we can analyze the sales of low rated products which are significant in number and take further steps to improve its sales if possible.
