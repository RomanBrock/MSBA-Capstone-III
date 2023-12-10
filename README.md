# Home Credit Default Risk | MSBA Capstone II

### Summary
---
Home Credit Group serves customers with insufficient or non-existent credit histories. Because of the nature of these customers, the inherent uncertainty around repayment ability is much higher. If repayment ability were less uncertain, the business could offer services to an even greater number of unbanked individuals, while remaining profitable. I believe that Home Credit Group can increase their ability to predict repayment by at least 15%.

I propose using alternative data such as telco and transactional information to predict repayment ability. A supervised classification model will be used to predict whether a client will default if we lend to them. A presentation will be delivered that outlines the model, data used, methodology, and any additional insights uncovered along the way. This project will be undertaken by 4 data scientists who expect to have it completed by 8/2/23. This team may deliver insights as they come across them, but the only expected deliverable should be the presentation.
### Solution
---
After initial exploratory data analysis and data we cleaned, our team tried 4 different models. After comparing the random forest, support vector machine, xgboost, and regression models, my team decided on an XGBoost (Extreme Gradient Boosting) model. The model contained 19 features, 7 tuned hyperparameters, 5-fold cross validation, and 50 iterations. It allowed us to predict default much better than before and also helped us gain knowledge about data available to us.
### Contribution
---
My biggest contributions for this project were building the random forest model and cleaning / joining the credit bureau data to the main dataset. My tuned random forest model took over 50 hours to run and when stored, was over 100 MB. Because of these limitations, it was not prudent to try to use and I ended up testing a more simplified random forest model contained in the combined modeling notebook.

I also aggregated, cleaned, and joined the bureau dataset up to our customer data. Several of these features were crucial in the model we put forward as the solution. In addtion, I helped design and build our presentation to help make our process easy to understand.
### Business Value
---
At the end of the day, we learned a lot about the available data and also built something that could save Home Credit some money. We learned that the external source features were pretty important in predicting default along with days employed and age. Our model would also give a 19.5% reduction of average lending risk AND would save around $38,000 in losses per client.
### Business Problems and Risks
---
This project contained many problems, risks, and challenges. These borrowers contained little or no credit history, which means that the data we have available to us is inconsistent and non-traditional. In addition, the majority class accounts for over 90% of the population, so our model has to be extremely precise in how it predicts default. Lastly, knowledge of the data is extremely limited. There was no subject matter expert or business conterpart to contact for help with what the data means or represents.
### What I Learned
---
I learned quite a bit about how hard it can be to get a high quality model built if data is extremely messy. I have dealt with constrained data constantly in my career, but have rarely had too much data to work with. It can be deceiving and even disorienting to have over 100 features if most of them are useless or filled with nulls. I also learned how valuable it can be to work with a team and try different things or have several eyes on the same set of issues. Overall, this was a great learning exercise and I am happy to have struggled through it.
