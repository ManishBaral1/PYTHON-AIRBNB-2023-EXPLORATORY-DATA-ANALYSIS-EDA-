# PYTHON-AIRBNB-EXPLORATORY-DATA-ANALYSIS-EDA-
![airbnb](airbnb.png)





### DATA SOURCE
The data for our EDA was taken from kaggle. Newyork City Airbnb 2023 data is a public data. (https://www.kaggle.com/datasets/godofoutcasts/new-york-city-airbnb-2023-public-data)


### Project Summary

This project is dedicated to performing exploratory data analysis (EDA) on Airbnb listings. With a global reach, Airbnb relies heavily on data analysis to enhance its operations. The platform generates extensive data from millions of listings, which can be leveraged for security, business decisions, understanding customer and provider behavior, innovation, marketing initiatives, and more. Our analysis focuses on historical data from Airbnb listings in New York, a prominent destination for tourism and business.

Our dataset contains approximately 49,931 records and 18 attributes. We began by importing the dataset and the necessary libraries to understand the variables. We performed comprehensive EDA, examining numeric and categorical features through univariate, bivariate, and multivariate analyses. Following this, we treated outliers and null values, transforming the data to ensure compatibility with model building and predictions if required.

**Overview**

1. Problem Statement
2. Know Your Data
3. Understanding Your Variables
4. EDA
5. Data Cleaning
6. Data Modeling and Prediction
7. Conclusion


### 1. Problem Statement

Airbnb is a prominent online marketplace that connects homeowners wishing to rent their properties with travelers seeking accommodations. It offers a straightforward, stress-free way for homeowners to generate income. New York City, a leading hub for tourism and business, is the focus of our analysis. Since its launch in 2008, Airbnb has broadened travel possibilities, offering unique and personalized experiences.

Airbnb's primary revenue stream comes from service fees on bookings. Guests often find Airbnb accommodations more affordable, characterful, and homelier than hotels. This project aims to:

- Conduct EDA on the dataset using Numpy and Pandas to uncover relationships between variables.
- Identify key features significant for Airbnb from a business perspective.
- Perform cost and revenue analysis to pinpoint groups where Airbnb can enhance profitability.
- Analyze customer ratings to discern sentiment and explore the relationship between price and user ratings.

### Business Context

Airbnb's innovative model has revolutionized the travel and hospitality industry, offering personalized experiences for travelers and a convenient income source for property owners. Data analysis is pivotal to Airbnb's strategy, enabling informed decision-making, ensuring security, and fostering innovation based on customer and provider behaviors.

### Data Cleaning and Preprocessing

Data cleaning is a crucial step in ensuring the accuracy and reliability of our analysis. We addressed null values by employing techniques such as imputation, where missing values were replaced with the mean or median of the column, and in some cases, dropped columns or rows with excessive missing data. Understanding and handling skewness in the data was essential; we applied log transformations to normalize skewed data.

Outliers were identified and treated using statistical methods and visualization tools. By using z-scores and IQR methods, we either corrected or removed extreme values that could skew the results. Visualization tools like Matplotlib and Seaborn were instrumental in this process, allowing us to graphically identify outliers and understand the distribution of our data.

**Natural Language Processing (NLP)**

We utilized the Natural Language Toolkit (nltk) library in Python to preprocess textual data before modeling. This included steps such as tokenization, removing stop words, and stemming. These preprocessing steps helped in transforming the text data into a format suitable for analysis and modeling.

### Data Modeling and Prediction

In addition to exploratory data analysis, we also undertook data modeling and prediction. We focused on predicting prices based on various attributes. We employed four different models using the powerful Scikit-Learn (sklearn) library:

1. **Linear Regression Model**
2. **Decision Tree Model**
3. **Lasso Model**
4. **Ridge Model**

Scikit-Learn is an essential library for machine learning in Python. It provides simple and efficient tools for data analysis and modeling, ensuring robust performance and ease of implementation. Our analysis revealed that the Decision Tree Model exhibited the highest R² value and the lowest error, making it the most effective model. Based on this model, we developed a recommendation system to aid in decision-making.



This project underscores the significance of data analysis in enhancing Airbnb's operational strategies, ensuring a better understanding of the market, and driving innovation and growth.



# THE FOLLOWING ACTIVITIES HAS BEEN DONE AND THE FOLLOWING QUESTIONS HAS BEEN ANSWERED IN THE JUPYTER(.pynb) FILE

### Activities done:
1. Data Extracting/Loading
2. Data Cleaning
3. Data Wrangling
4. Data Exploration
5. Data Visualization
6. Data Modeling and Prediction

### Questions answered?
1. What are the most listed hotel name present in Airbnb Newyork in 2023?
2. What are the most listed host name present in Airbnb NYC listing 2023?
3. Which neighbourhood geoup has highest listing and we try to show neighbourhood group vs price?
4. Which neighbourhood has highest listing and we try to show neighbourhood vs price?
5. Visualization by latitude and longitude?
6. Visualization by roomtype?
7. Visualization by price?
8. Graphs by Minimum nights, number of reviews and availability 365?
9. Handling missing values?
10. Handling the outliers and skewness?
11. What is the average price by room type?
12. Which room type has more reviews?
13. What is the room type preference in different neighbourhoods?
14. What is the seasonal trend in airbnb prices?
15. Which neighbourhood has more reviews?
16. What are top 5 neighbourhood by listing count in each neighbourhood group?
17. What is average availability by neighbourhood group?
18. What are the correlations among the selected columns including price?
19. What is price distribution?
20. What are number of reviews vs price?
21. What is average price by neighbourhood group?
22. Who are top 5 hosts who own most property?
23. Who are most expensive hosts?
### DATA MODELLING AND DATA PREDICTION
### Model= Price Prediction based on name
24. Linear Regression Model , Decision Tree model, Ridge model and Lasso model
**We showed Decision Tree model has the highest R^2 value and least error. Hence it is the best model.**
25. Created Recommender System



