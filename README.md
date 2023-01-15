# Data Science Salary Predictor (during COVID-19)

- Created a project that estimates Data Science salaries (MAE~\$20k) to help data scientists better understand what salaries they might expect during COVID-19
- Webscraped job data from Glassdoor using Selenium and Chromedriver
- Feature engineered from the text of the job description to quantify the value companies place on skills like Python, R, AWS, Hadoop and many other skills, and also knowledge required typically like Algorithmic Knowledge and Statistical Knowledge.
- Optimized Linear, Lasso and Random Forest Regressors using GridsearchCV to reach the best model.

## Motivation

(Inspired by Ken Jee's Youtube Playlist: [Github Repo](https://github.com/PlayingNumbers/ds_salary_proj))

During the COVID-19 pandemic, employment levels have reached new lows. The tech industry has also been affected by this, and subsequently, Data Scientists as well. Being able to get a good job right now, with a salary proportionate to the skills they possess is important, and at the same time, much more different compared to more normal period of time. This tool provides a means to help estimate how much salary one might recieve right now, based on their skills, as well as the company hiring them.

## Technologies Used

This project primarily uses Selenium, Numpy, Pandas, Joblib and Scikit_Learn.

## Environment Used

All the code was using VScode

## Models Used

Comparisions were made with a Linear Regression Model (MAE ~25K), Lasso Regression Model (MAE ~22K) and a Random Forest model (MAE ~23K), and GridSearchCV helped identify the optimal hyperparameters for tuning each of these models, attaining a Lasso Regression Model with (MAE ~20K).

## EDA Result

Some interesting results from the EDA:

![Plot1](/images/plot1.png)

![Plot2](/images/plot2.png)

![Plot3](/images/plot3.png)

![Plot4](/images/plot4.png)

