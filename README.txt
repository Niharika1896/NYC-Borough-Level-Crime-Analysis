This project throws light on how education, mental health, and alcohol consumption affect the type of crimes occurring in the 5 NYC boroughs (Staten Island, Manhattan, Brooklyn, Bronx and Queens).
Descriptive analytics show the existing trend of schooling, alcohol consumption and mental health in the 5 NYC boroughs. (2017-2021)
We implemented predictive analytics models (classification models) to understand the type of crime occurring in the boroughs based on these factors.

Major steps through the project lifecycle:
1.	Data aggregation: 6 types of datasets considered, giving a total of more than 10 million datapoints. 
i.	NYPD Arrests data(historic)
ii.	NYPD Shooting Incidents data(historic)
iii.	NYPD Hate Crimes 
iv.	Demographic Snapshot (for education data)
v.	Hospital Inpatient Discharges (for mental health data)
vi.	Liquor Authority Current List of Active Licenses (for alcohol data)
2.	Data Understanding: This phase requires a deeper study of the aggregated datasets. Choosing the right type of data is extremely crucial. Any model’s result is as good as the data the model is applied on, hence a thorough understanding of the information a dataset conveys is of extreme importance. 
3.	Data preparations: Data is cleaned and transformed to make it ready for analysis. For example, only a few select columns (or features) are generally required for data modelling. This step involves data cleaning, missing value imputation, treatment of outlier values, checking for class imbalance, feature engineering (feature reduction, feature selection) and data transformation. The 4 datasets are combined to produce a single dataset on which the modelling algorithms will run. 
4.	Data modelling and analysis: Selecting the classification model to apply on the dataset to predict the type of crime based on the 3 factors. 
