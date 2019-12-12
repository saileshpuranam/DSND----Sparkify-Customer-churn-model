
# Sparkify — User churn prediction model using Pyspark

### Project Motivation and Objective

Sparkify is a fictional music app on which users can purchase a subscription and have access to all latest music albums from various artists. Identifying which users are at risk to churn - either by downgrading from premium to free , or cancelling their service, can help Sparkify save money by attempting to retain the customer through various means like coupons, incentives etc.

The objective of this project is to create a machine learning model that can predict the customer churn with good accuracy. We are going to use the Pyspark platform to execute this project.

### Datasets Used

Actual full size data set is 12GB and it is difficult t0 rrocess data that big on local machines. So I used a subset of size 125 MB of the original provided by Udacity for analysis and prediction purposes. The data we have is user activity tracked by the app which records artist, song, duration, user information time stamps and other relevant information.

Before we start with Feature selection and machine learning, we should understand the data set thoroughly and decide which variable/features we would like to use for training the model.

Each of the steps involved in project execution are explaind in detail in my blogpost on medium. Please refer to the link provided in below sections to access the same

### Python Packages used

This project is executed in a Jupyter Notebook with the help of below packages

1. numpy
2. pandas
3. matplotlib
4. seaborn
5. datetime
6. pyspark.sql
7. pyspark.ml

### Github Repo Contents

1. Sparkify - Predict customer churn.ipynb
2. Project README file
3. Link to the blogpost

### Link to the Blogpost

https://medium.com/@saileshpuranam92/sparkify-user-churn-prediction-model-using-pyspark-3842d8bb10eb

### Acknowledgements and Licensing

Datatsets for this project are exctracted through the Udacity course 

Feel free use the code and other info in this repo for all your references whenever required.
