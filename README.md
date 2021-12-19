# Price-Suggestion---Modelling
Problem Statement: It can be hard to know how much something’s really worth. Lets say we have two sweaters and now in order to decide what price the product should have is a task. Product pricing gets even harder at scale, considering just how many products are sold online. Clothing has strong seasonal pricing trends and is heavily influenced by brand names, while electronics have fluctuating prices based on product specs.

Challenges to Solve: Given details about a product like product category name, brand name, and item condition, our challenge is to build an algorithm that automatically suggests the right product prices. This way the human interfernce in giving price suggestions reduces manifolds and thereby it increases the efficiency also.

The task of this Project is to build an algorithm that suggests the right product prices from product name, category name, brand name, item condition, and shipping information.

The goal is about creating a model that would help sellers to price their products.Pricing should be intermediate between sellers and buyers

Our Objectives: • Data Cleaning • Feature Engineering • Using various Machine Learning Models

Exploratory Data Analysis:

Gathering as many insights as possible through Exploratory Data Analysis. Giving the relation between various independent variable and dependent variables so that visual representation could be drawn For the visual representation, various plots have been used such as boxplot, bar plots, pie charts etc

Feature Engineering : The various variables has been checked if there are any null values to be taken care of and those null values has been replaced accordingly One Hot Encoding has been done on variables so that we can get the data in numeric format as machine learning cant understand raw text and finally various models has been applied

Modelling: The given problem is exactly about predicting the price, which is a real-valued value, thus it falls into the Regression Category, thereby have used SGD, Ridge Regression and Linear Regression Finally, pretty table has been made so that the rmse could be figured out for the models Trying to provide some interpretability and evolving our ways to handle the upcoming problems as we proceed through our project
