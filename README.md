# Airline-Passenger-Satisfaction-Prediction

⦁	Introduction:

The dataset used was about an airline passenger satisfaction survey. There are two stakeholders that are going to use the analytical output from this dataset. The first stakeholder is the Head of Analytics Team who wants to know the best model that can be presented to the business team to perform prediction regularly. The second stakeholder is the representative from the business team who is going to take the best model and any insight/finding to his/her regular business meeting.

⦁	Task:
- What is the best possible machine learning algorithm that can be presented to the representative of the business team?
- Find any useful insight or finding that the representative of the business team might interested in.

⦁	Content:

First and foremost, I performed data cleaning and manipulation processes to transform the data so that it could be best suited to use for supervised learning algorithms. Second, I checked for the presence of multicollinearity in the data and I found out that multicollinearity occured. Third, I implemented seven classification algorithms, specifically logistic regression with L2 regularisation (to mitigate the possible drawbacks of multicollinearity), decision tree, artificial neural network using multi-layer perceptrons, random forest, gradient boosting classifier, bagging classifier with logistic regression as the base estimator, and extreme gradient boosting classifier. I found out that the later model is the best model because it has the best performance on the validation data (based on the precision score) and it did not experience overfitting. Finally, from all seven models, I found out some business insights for the business team, such as longer distance flights are more likely to be associated with higher satisfaction (which could indicate that longer flights may offer better services), male passengers are more likely to be satisfied compared to the females, and the most important or contributing feature to customers' satisfaction is customers satisfaction level with the airline's online onboarding process.
