# Ad_Click_Prediction
Overview
Advertisements are really important in today’s world and with increasing penetration of digital media. With the popularity of the Internet, businesses can put ads on the Internet, people can choose to watch, for the website and business mutual benefit. It is very interesting to see how people would like to spend their time on the internet every day and what kind of content could attract different age group, income level and location. From the analysis of how people interact with advertising on interest, businesses could create better ad to develop their companies.

Business Problem
We will predict which users are more likely to click an advertisement based on user’s demographic data and features of advertisement.

Dataset Overview
The data is from public data recourse: https://www.kaggle.com/fayomi/advertising.

The dataset structure demonstrates that it is included by 1000 observations and 10 variables. The variables are the demographic data that describe the users as below:

Daily.Time.Spend.On.Site: It is the total time (in minutes) that the user spends on the website (continuous numeric data)
Age: Age of the users in years (continuous numeric data)
Area.Icome: Income of the area where a user visited the website in US$ (continuous numeric data)
Daily.Internet.Usage: Amount of time spent on the internet usage in minutes (continuous numeric data)
Ad.Topic.Line: Title of the advertisements that popped up on the website (Character data)
City: City of the user (Character data)
Male: Categorical data whether the user is male or not (1 means user is a male and 0 means otherwise)
Country: Region (Country) of the user (Character data)
Timestamp: Timestamp when the user clicked the advertisement (date-time)
Clicked.on.Ad: Categorical data if the user actually clicked on the website (1 = yes and 0 otherwise)
Approach
We will divide the business problem into two major parts.

We will conduct data cleaning and perform an exploratory data analysis to generate some insights on the clicking behavior of the users

We will count the frequency of most repeating words from the advertisement title. These keywords should be the area of focus for designing the advertisement titles

We will build features to enhance the predicting capability of the model

We plan to develop **Logistic Regression, Naïve Bayes, and Decision Tree** for this classification problem

We will be using the accuracy as a metric for model comparison
