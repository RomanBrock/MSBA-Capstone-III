# Maverik Revenue Forecasting | MSBA Capstone III

### Summary
---
Maverik needs an accurate daily forecast of sales KPIs for a new store's first year of sales. Achieving this allows for more effective financial planning and accurate ROI documents. This project will be a success if it is able to yield a better forecast than the current model. Stakeholders will measure success with error rate RMSE, MAPE, model fit (AIC &, R²), and overall accuracy. This is a supervised regression problem where the predictors involve both categorical and numerical variables, and the target are four sales metrics. In order to solve this problem, we will conduct exploratory data analysis, train forecasting models like XGBoost machine learning and ARIMA time-series, evaluate models on success metrics and provide predictions using the chosen model.

The deliverable will be a predictive model that produces daily sales forecasts for each sales metric. This model will consider store features, seasonality, as well as having capability to process new data and re-forecast. This project will be executed by Biva Sherchan, Roman Brock, Bhoomika John Pedely and Pablo Zarate. We will submit our exploratory data analysis on October 8, 2023, and a notebook of the forecasting model on November 5, 2023. We will deliver a presentation of our findings to Maverik on November 30, 2023.
### Solution
---
After initial exploratory data analysis and adding in additional features (like national gas and diesel prices), our team tried 4 different models. After comparing the XGBoost, ARIMA, ETS, and Prophet models, my team decided on a Prophet model. The model allowed us to predict sales for 4 different sales metrics for the first year, able to ingest actuals to improve future predictions.
### Contribution
---
My biggest contributions for this project were building the XGBoost model and doing analysis / providing visuals for correlations between our target variables. My XGBoost model performed admirably, but it was ultimately not the model that performed best in our tests. I also provided input and helped interpret our EDA findings.

I assisted in designing and building our presentation to help make our process easy to understand. I also played an active role in helping the team present efficiently and in a way that is preferred for business settings.
### Business Value
---
At the end of the day, we built something that could save Maverik save money and improve operations via better ROI analysis when opening new stores, better inventory management, and better site selection for new stores. We also learned that the external external gas / diesel pridces were pretty important in predicting sales. Our model would give a 73% reduction in prediction error for our hold out store.
### Business Problems and Risks
---
This project contained many problems, risks, and challenges. We had to create 4 separate predictions (one for each sales KPI) and also could not use the respective KPIs as predictors for one another. The models also had to be rolling (able to take in actuals and reforecast). We had limited knowledge in the specific domain and there were variations in seasonality / sales volumes across stores. In addition, this type of modeling is computationally demanding and takes a lot of time.
### What I Learned
---
I learned quite a bit about the difficulty of creating a rolling forecast model. I have created forecasts in my career before, but the complexity and automation of this one was much more challenging. I also realized how important external data is and how influential one feature can be for model performance. I learned how valuable it can be to work with a team and try different things or have several eyes on the same set of issues. Overall, this was a great learning exercise and I am happy to have struggled through it.
