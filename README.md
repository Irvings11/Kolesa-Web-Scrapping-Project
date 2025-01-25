This is a review of the web scraping website Kolesa.kz, where people can sell and buy cars, various spare parts.
Users can find out prices, brand, type, year, etc. And let's say I want to choose a car to buy, we look at prices, specifications, year, using web scraping,
namely Beatifulsoup and the pandas library, we were able to extract all the data from the website and transfer it to a convenient table. By cleaning the data,
I was able to extract more than 1000 data, 952 rows and 16 columns. After careful data processing, I added special Python libraries for machine learning and more.
Important libraries such as: Patsy, scikit-learn, statsmodel. For example, the result of the OLS regression showed R-squared is 0.595,
which shows the coefficient of variation of prices is more than half. Also I used scikit-learn library for linear regression to show how year and engine size interact with each other,
and determine the price predictions, and the R-squared showed 0.63 coefficient, which shows a more satisfactory result. Also with the same data, we used Logistic Regression, 
the accuracy is 79.6 percent, and the confusion matrix shows 119 and 33 are correct predictions for each class,
8 and 31 are incorrect predictions, so the model showed a good classification.
![image](https://github.com/user-attachments/assets/f1cda1fc-a87e-4de9-85cb-987620126ce0)
