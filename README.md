# Bank-marketing-effectiveness-prediction
Telemarketing is a widely adopted direct marketing technique in banks. Since customers hardly respond positively, data prediction models can help in selecting the most likely prospective customers. We aim to develop a classifier accuracy to predict which customer will subscribe to a long-term deposit proposed by a bank.

As the first step, we have started with Exploratory Data Analysis in which two type of variables has been separated that is categorical and numerical variables and monitored each variable with the help of histograms. Also we have used sweetviz library to check the distribution of all variables with dependent variables.

Further, Data cleaning have been performed in which unknown values in the categorical variable ‘education’ and ‘job’ was filled with the mode while the unknown variable in the columns 'poutcome', 'contact','balance', 'duration' are much greater so we have droped the colums. 
 
Further, we have checked the correlation between all numerical variables and woked accordingly. 

Then, we have done Lable Encoding and One Hot Encoding to change categorical variable to numerical variables for machine to understand the values. Further we have done Synthetic Minority Oversampling Technique to handle the class imbalance dataset and also we done stahdardisation to scale the data.

Further, we applied various model on the data which we split into train and test dataset. The model which we have applied are Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, eXtreme Gradient Boosting, CAT Boosting, K-Nearest Neighbour and we done the evalution of the all models using confusion matrix and AUC-ROC curve.
