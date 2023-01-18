# Starbucks-Customers-Satisfaction

This dataset about Starbucks which is American multinational company for coffeehouses and Beverages. Basically, this dataset contains information from Starbucks surveys, which are critical for any business to analyse to enhance services and product sales. The dataset's insights come from surveys of customers about their preferences for dining in or ordering takeout, how much they spend overall on products and services, and whether they would return to Starbucks.

The project is going to predict the most important factor which is bring back (loyal customer) to customer in Starbucks and use various machine learning algorithms to predict loyal customers by using the smaller number of features (membership, quality, and price) with best accurate result possible. This method will help Starbucks to take decision on their services as well as quality of the food or several offers for membership faster based on the features and analysis that customer behaviour on purchase based on that they can give several offers and rewards points to bring them in Starbucks. 

As a result, Starbucks will pay more attention to bringing in consistent consumers and will be able to increase sales by knowing how loyal their customers. 

Steps for execution:

Extracted the Data

Perfromed EDA for the different features to check how they ar correlated and do the analysis of every features with loyal custmoers

Split and Explode the data according 'Products' and 'MethodsOfVisitsStarbucks' and create new csv file

Drop some column and Replace null value of nan and i dont like and never 'Method' with 'Never'

Label the Categorical Values

Perfromed a train_train_split for the data to split it into 80% training and 20% testing data.

Created a Machine Learning Model using LogisticRegression, Decision Tree, Random Forest, XG Gradient Boosting by tuning the models.

Trained a model and made predictions.

Plot a confusion matrix for each method and select the optimal algorithm with the highest accuracy and the most essential attribute.

Calculate y_test-predictions.
