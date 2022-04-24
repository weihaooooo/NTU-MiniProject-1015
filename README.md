# Welcome to Football Match Prediction Repository

## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on predicting football matches' outcome from the English Premier League. For detailed walkthrough, please view the source code in order from:

1. EPLDataPrep
2. Exploratory Data Analysis
3. ML_Model Logistic_Regression
4. ML_Model SVM
5. ML_Model XGBoost
6. ML_Model Neural Network
7. Random Forest + DT

## Contributors
- Hemanth: Data Prep, Neural Network
- Yuan Lin: SVM, XGBoost, Logistic Regression
- Wei Hao: EDA, Decision Tree, Random Forest

## Problem Definition
- Are we able to predict the outcome of a football match before it occurs using past predictors? (Utilising historical data)
- Which model would be the best to predict it?

## Dataset
Dataset for this project is from  https://www.football-data.co.uk/. We focused on training our model with data from English Premier League.

## Machine Learning Techniques Used
This project makes use of Neural Network, Xgboost, Support Vector Machine, Logistic Regression, Random Forest and Decision Tree to predict outcomes using the data given.

## Conclusion
- The betting odds and the outcome of a football match has a low correlation
- The recent form of a team has a low correlation with football match outcome as well
- Hypertuning our existing models proved crucial in improving the performance of the models
- Despite the fact that almost all models did not achieve a very high accuracy, when applied to a real life situation it performed significantly well 
- XGBoost proved to the most effective model to use to obtain the most profitable betting strategy
- The models can be used to predict specific outcomes to improve their effectiveness
- All in all, it is possible to predict a football match outcome without knowledge about the match statistics 

## What did we learn from this project?
- Neural Networks, Keras and Tensorflow
- Logistic Regression from sklearn
- SVM from sklearn
- XGBoost
- Usage of Decision Tree and Random Forest
- Other packages 
- Collaborating using GitHub
- Concepts about Precision, Recall, and F1 Score

## References
- https://www.analyticsvidhya.com/blog/2021/06/understanding-random-forest/#:~:text=Random%20forest%20is%20a%20Supervised,average%20in%20case%20of%20regression.
- https://www.mastersindatascience.org/learning/introduction-to-machine-learning-algorithms/decision-tree/#:~:text=A%20decision%20tree%20is%20a,that%20contains%20the%20desired%20categorization.
- https://www.techtarget.com/searchbusinessanalytics/definition/logistic-regression#:~:text=Logistic%20regression%20is%20a%20statistical,or%20more%20existing%20independent%20variables.
- https://www.nvidia.com/en-us/glossary/data-science/xgboost/#:~:text=XGBoost%2C%20which%20stands%20for%20Extreme,%2C%20classification%2C%20and%20ranking%20problems.
- https://www.kdnuggets.com/2016/07/support-vector-machines-simple-explanation.html
- https://www.investopedia.com/terms/n/neuralnetwork.asp#:~:text=A%20neural%20network%20is%20a,organic%20or%20artificial%20in%20nature.
- https://totalfootballanalysis.com/opinion/football-betting-the-global-gambling-industry-worth-billions

