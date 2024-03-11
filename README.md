Step 1: Business Inquiry

I am examining a health insurance dataset to forecast future insurance costs, and the dataset can be accessed on GitHub insurance dataset.
The dataset comprises 1338 entries with 7 attributes. The primary goal here is to enhance the accuracy of predicting the target variable. To achieve this, I employ two machine learning models.

Parameters in the dataset include:

•	Age: The age of the insured (integer).
•	Gender: Gender of the insured.
•	BMI: Body Mass Index of the insured (float).
•	No_of_Children: Number of children the insured person has (integer).
•	Smoker: Whether the insured person is a smoker or not.
•	Region: Region of the USA to which the insured belongs.
•	Charges: Insurance charges in USD (float).


Step 2: Data Processing

1.	First, I read the data description and checked for null values.
2.	Next, I handled outliers by using boxplots.

Step 3.	Data Exploration:
   
Explored the relationships between different features to understand their correlations and impact.

Step 4: Data Modeling

I utilized two machine learning models, Decision Tree and Random Forest, to predict insurance costs. 
After evaluating metrics like RMSE, MAE, and R2 score, Random Forest outperformed Decision Tree.

Feature Importance Analysis: Explored feature importance to identify the most influential factors for predicting charges. Age and Smoker_encoded emerged as the top features.

These findings offer valuable insights for refining insurance cost predictions, with Age and Smoker status taking the lead in shaping future charges.
