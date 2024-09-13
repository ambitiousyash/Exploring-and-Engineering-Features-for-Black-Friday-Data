# Exploring-and-Engineering-Features-for-Black-Friday-Data

Problem Statement:
ABC Private Limited, a retail business, is interested in knowing how customers make purchases (more especially, how much they spend) in relation to different products across different categories. They have released the purchase histories of a number of clients for a few high-volume items from the previous month. The data set also includes product specifics (product id and product category), total purchase amount from the previous month, and consumer demographics (age, gender, marital status, city type, stay in current city).

1)Comprehending the Information
*Gaining insight into the dataset.
*Seeking for: Missing values, categorical variables, etc.

2)observation:
*Categorical Factors in - Age, Gender, City Category
*We can disregard the missing values in Product_Category_2, Product_Category_3, and User_ID because they are not significant.
*Missing/Null Values in - Product_Category_2, Product_Category_3, Purchase
*Column- 'Stay_In_Current_City_Years' datatype is object and we need to convert that into an integer

3)Data Visualisation:
Observations -
*Purchasing of men is higher than women
*Purchasing for Occupation 17 on an average is higher than any other.
*Product category 1 is bought most (approximately 20,000)
*Marital Status has no impact on purchasing.
*Purchasing of men is higher than women.
*Purchasing of products - Product 1 > Product 3 > Product 2
*Max purchase is around 7000

4)Data preparation and transformation
*Feature engineering/scaling
