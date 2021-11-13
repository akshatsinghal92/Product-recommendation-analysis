# Product-recommendation-analysis
## Business problem:
- If any product is purchased on the client's website, it receives a rating and reviews based on its taste, price, etc.
- Based on these factors, the product may or may not be recommended further.
- But sometimes, the recommendation details about a product are missing on the webpage. It is difficult for the customer to categorise it as a good or bad product just based on ratings and reviews. 
- So, the main problem is to investigate the possible reason for the missing recommendation details and find a way to predict the recommendation details for such products.
## Techniques involved:
- Web extraction using Selenium
- Data analytics and visualisations on extracted dataset using seaborn plots
- Sentiment analysis on product reviews using textblob
- Word embeddings generation from reviews using Universal sentence encoder (transformer)
- Regression modelling with Random Forest, Xgboost, and Lasso regressor models
- Comparing performance improvements of models as more information is made available to the ML model.
- Interpretation and comparison of models using PDP plots, Q-Q, and histogram plots of residuals
## Conclusion:
- Based on the reviews and ratings of various users for different products, this model predicts a recommendation score, which gives an even clearer picture compared to manual recommendation feedback given by customers.
- As recommendation score for some products is very low, we can analyse the number of sales and revenue for these products.
Based on that, we can decide whether to invest in those or focus on other revenue-generating products.
- Also, we can analyse the sales of low rated products that are significant in number and take further steps to improve their sales if possible.
