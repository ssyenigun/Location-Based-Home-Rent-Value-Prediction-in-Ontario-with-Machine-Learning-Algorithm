# LOCATION BASED HOME RENT VALUE PREDICTION in ONTARIO WITH MACHINE LEARNING ALGORITHM

Following Stages:
This capstone project analyzes over 2,850 Ontario listings on Realtor.com, with 20 attributes like property data and crime rates. 
Through data cleaning, exploratory data analysis, and predictive modeling, it researches the effects of building size, bedrooms, bathrooms, and crime rates on rent prices. 
This is the step and process of the Location-Based Rent Value Prediction Model project. 
This project aims to develop a model that can predict the rent value of properties based on their location and other characteristics.


1. Research Papers Reviewed
An adequate number of research papers from Kaggle, GeeksforGeeks, scholarly websites, and crime index resources were read. These are case studies of house rent prediction based on regression models without any advanced feature engineering.
•
https://www.kaggle.com/code/rkb0023/exploratory-data-analysis-house-rent-prediction
•
https://www.geeksforgeeks.org/house-price-prediction-using-machine-learning-in-python/
•
chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://kth.diva-portal.org/smash/get/diva2:1805004/FULLTEXT02.pdf
2. Relevance of Cited Articles
Papers were chosen according to their relevance to rental forecasting, regression modeling, and application of geospatial or crime data in pricing. Each reference was matched to principal features of this project such as predictive analytics and real estate market modeling.
3. Overview of Every Paper
Summaries were authored for each paper, topics such as:
- Methods of rent forecasting via regression
- Influence of location on housing affordability
- Usage of external indicators such as crime rates
- Preprocessing tactics for property listings
4. Data Cleaning and Correlation
Multiple cleaning procedures were done on the data:
- Elimination of duplicate URLs
- Normalization of dates (DD/MM/YYYY)
- Imputation of missing values through Random Forest
- Outlier detection through Z-score
Correlation among property price, size, and number of rooms was checked; moderate-to-strong correlation was observed.
5. Research Questions
Primary questions:
- How do building size, bedrooms, and bathrooms affect rent?
- Does crime rate an influence that affects rental prices?
- Is it possible for a prediction model to project rent with high accuracy based on these variables?
6. Outlier Data & Dataset Connection
Z-score analysis was used to identify outliers. Unusual values in building size and price were marked. The working dataset was manually pulled from Realtor.com listings.
7. Remarks Regarding the Data
Remarks were made to explain why some rows had been deleted or changed. Notes regarding high-crime vs. high-rent cities were provided.
8. Methods from Prior Research
Random Forest and Linear Regression were selected from earlier studies showing excellent effectiveness on non-linear real estate data. Feature engineering and model interpretability techniques were proposed based on earlier case studies.
9. Comprehensive Methodology
The project employed a rigorous methodology:
- Realtor.com & CanadaCrimeReport.com
- Cleaning and conversion (like one-hot encoding and Z-scores)
- Exploratory analysis (EDA visualization and clustering)
- Training and testing of models (Random Forest, SVR, Linear Regression)
- Testing on MSE, RMSE, R²
10. Report Structure & Consistency
The report was structured well with sections appropriately titled for data handling, modeling, and business insights. Interpretations were followed by visuals, and the conclusion linked technical findings to strategic applications.
