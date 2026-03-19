Notebook 1: Cardiovascular Disease (CVD) PredictionOverview:
This project aims to predict the General_Health status of individuals based on various health indicators and lifestyle habits 
using a cleaned cardiovascular disease dataset. The project compares the performance of three different machine learning 
classifiers.

Data Preprocessing: Handled categorical variables using LabelEncoder and get_dummies.
Feature Scaling: Applied StandardScaler to normalize numerical features, ensuring models like SVC and Logistic Regression 
converge efficiently.

Modeling: 
Implemented and trained three models:
Linear SVC: Chosen for faster computation on the dataset.
Logistic Regression: Used as a baseline probabilistic classifier.
Random Forest: An ensemble method to capture non-linear relationships.

Results Model Accuracy:
1. Logistic Regression = 0.43 (Highest)
2. SVC (Linear) = 0.42
3. Random Forest = 0.41
The models show similar performance, with Logistic Regression slightly outperforming the others in predicting the general
health category.


Notebook 2: Housing Market Exploratory Data Analysis (EDA):
A comprehensive analysis of housing data to identify how features like price, square footage, air conditioning, and parking 
influence market trends.

Key Insights & Visualizations:
1. Price DistributionWe categorized houses into five price brackets. 
   The majority of the inventory falls within the 26–50 Lakh range, showing a sharp decline as prices exceed 75 Lakhs.
2. Impact of Air ConditioningThere is a significant price premium for climate control. Houses with AC command an average
   price of approximately 6M, compared to 4.2M for those without.
3. Parking Availability vs. PriceThe data suggests that increasing the number of parking slots correlates with higher property
    values, peaking at the 2-slot mark.
4. Premium Feature Analysis (The "Price Gap")We compared "Standard" houses (Small area & no preferred area) against "Premium"
   houses (Large area & preferred area):Standard (<5000 sqft, no prefarea): Avg. Price ≈ 3.83M Premium (>5000 sqft, prefarea):
   Avg. Price ≈ 6.55M .The Price Gap: 2,719,136.

Technologies Used: Python programming language.
Pandas: Data manipulation and cleaning.
Scikit-Learn: Machine learning and preprocessing.
Matplotlib & Seaborn: Data visualization.
