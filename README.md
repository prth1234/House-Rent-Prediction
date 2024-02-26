
# House Rent Prediction

## Project Synopsis

**Machine Intelligence**

**Bachelor of Technology - V Sem CSE**  
**Department of Computer Science & Engineering**

### Submitted by
Parth Singh          |         PES2UG20CS914 

**PES University**  
(Established under Karnataka Act No. 16 of 2013)  
100 Feet Ring Road, BSK III Stage, Bengaluru-560085

## Abstract and Scope

The House Rent Prediction project aims to leverage Machine Intelligence to predict house rent values based on various parameters such as BHK, Rent, Size, No. of Floors, Area Type, Area Locality, City, Furnishing Status, Type of Tenant Preferred, No. of Bathrooms, and Point of Contact. The project involves extensive data analysis, outlier handling, and the training of multiple machine learning algorithms to achieve accurate rent predictions.

### Feasibility Study

The project addresses the need for efficient and accurate house rent prediction, considering the numerous factors influencing rental values. Machine Intelligence algorithms provide a practical solution to handle complex datasets and deliver accurate predictions, making the project feasible and valuable.

## Design Approach/Methodology/Planning of Work

The project follows a structured methodology that includes:

1. **Exploratory Data Analysis (EDA):** Identifying outliers, analyzing data distributions, and determining influential factors.
2. **Data Preprocessing:** Handling outliers, removing irrelevant variables, and preparing the dataset for model training.
3. **Model Training:** Utilizing 11 different machine learning algorithms, including linear regression, ridge regression, XGBoost, CatBoost, LightGBM, gradient boosting, LASSO, random forest, Bayesian ridge, support vector, and k-nearest neighbors.
4. **Evaluation:** Comparing algorithm performance using various evaluation metrics to identify the most accurate model for house rent prediction.

### References
Paper1: 
https://www.researchgate.net/publication/349227005_Predicting_the_rental_value_of_houses_in_household_surveys_in_Tanzania_Uganda_and_Malawi_Evaluations_of_hedonic_pricing_and_machine_learning_approaches
<br> Paper 2:
(PDF) Housing Price Prediction via Improved Machine Learning Techniques (researchgate.net)
<br> Paper 3:
<br> Monitoring housing rental prices based on social media:An integrated approach of machine-learning algorithms and hedonic modeling to inform equitable housing policies - ScienceDirect
<br> Paper 4:
Monitoring housing rental prices based on social media:An integrated approach of machine-learning algorithms and hedonic modeling to inform equitable housing policies - ScienceDirect
<br> Paper 5:
https://paperswithcode.com/paper/house-price-prediction-using-lstm
<br> Paper 6:
(PDF) House Price Prediction Using Random Forest Machine Learning Technique. (sciencedirect.com)

## Dataset used :
https://www.kaggle.com/datasets/iamsouravbanerjee/house-rent-prediction-dataset

## Abstract

### Problem Statement

Renting, also known as hiring or letting, involves a temporary agreement for the use of a property. The project addresses the challenge of predicting house rent values based on multiple parameters, offering valuable insights for both tenants and landlords.

### Overview

The dataset contains information on 4700+ houses/apartments/flats available for rent, each with various parameters. The project involves:

1. **Exploratory Data Analysis (EDA):** Identify outliers and influential features.
2. **Data Preprocessing:** Handle outliers, remove irrelevant variables, and prepare the dataset.
3. **Model Training:** Utilize 11 different machine learning algorithms for accurate rent predictions.

## Literature Review

The project's literature review explores various models and techniques used in related papers. The selected model, LightGBM, was chosen based on its advantages and suitability for the dataset.

### Models Used in Literature Review

1. Ridge Regression, LASSO, Tree Regression, Bagging, Random Forest, and Boosting.
2. XGBoost, LightGBM, Random Forest Technique.
3. Hedonic Regression Model with six different machine learning algorithms.
4. A combination of linear, non-linear, and ensemble algorithms.
5. Random Forest Machine Learning.
6. Long Short-Term Memory (LSTM).

### Implementation

After performing EDA, outliers were addressed, and boxcox transformations were applied. The dataset was divided into training and test data. Eleven machine learning algorithms were trained and evaluated.

## Results

The project's results showcase the performance of four variants of GraphDTA models compared to existing baseline models. The best-performing variant achieved a 14.0% improvement in Mean Squared Error (MSE) for the Davis dataset. For the Kiba dataset, three of the four variants had the lowest MSE and the highest Concordance Index (CI).

### Model Interpretation

An analysis of latent variables within the GraphDTA model was conducted through redundancy analysis. The GIN model showed superior performance, and post hoc statistical analyses were focused on it.

## Implementation and Usage

1. Clone the repository:

   git clone https://github.com/prth1234/House-Rent-Prediction.git
   
2. Explore Jupyter Notebooks for data analysis and model training.

Dataset Used
House Rent Prediction Dataset: https://www.kaggle.com/datasets/iamsouravbanerjee/house-rent-prediction-dataset

