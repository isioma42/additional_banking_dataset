# additional_banking_dataset

Emory Applied DS & ML with Python Program 
Capstone Project - Python
This capstone project is designed to give you an opportunity to leverage exploratory skills, research abilities, and in-class learning and to apply that knowledge in analyzing a real-world data set in a wholistic manner. Best way to learn and master any technology or skill is by doing it. Data analytics in particular is all about asking the right questions, identifying appropriate resources, investigating the appropriate techniques, and applying them in an iterative manner. Working on this project therefore may involve concepts and techniques in addition to what were taught in the class keeping in line with the real-world scenarios which necessitate self-learning and exploratory research. 
For this project, you will be working on a marketing data set related to a banking institution (obtained from UCI Machine learning repository). You will be performing various tasks in Python as described below:
I.	Data Collection 
1)	Load the ‘bank-additional-full.csv’ dataset. Identify the number of rows and columns. Get familiar with the bank dataset features (or attributes):
Client features
age, job, marital status, education, default: (has credit in default?), housing: (has housing loan?), loan: (has personal loan?)

Features related with the last contact of the current campaign:
contact: (contact communication type), month: (last contact month of year), day_of_week: (last contact day of the week), duration: last contact duration, in seconds. 

Other features:
campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
pdays: number of days that passed by after the client was last contacted from a previous campaign (999 means client was not previously contacted)
previous: number of contacts performed before this campaign and for this client 
poutcome: outcome of the previous marketing campaign 

Social and economic context features
emp.var.rate: employment variation rate - quarterly indicator
cons.price.idx: consumer price index - monthly indicator 
cons.conf.idx: consumer confidence index - monthly indicator 
euribor3m: euribor 3 month rate - daily indicator 
nr.employed: number of employees - quarterly indicator 

Target variable
y – has the client subscribed to a term deposit or not??

II.	Preliminary Data Exploration 
2)	Identify the number of unique values for each attribute

3)	How many categories of attributes are there? Identify variables that can be treated as continuous and variables which can be treated as categorical. 


4)	Are there any missing values in the data set? If so, identify which columns have missing values and how many missing values. Explain your strategies for dealing with missing data for each column with a missing value. Please explain why you chose a particular strategy (this question applies only if any missing values are present)

5)	Are there any duplicates, outliers and any inconsistencies? Does it make sense to keep or remove any duplicates?

6)	Identify the proportion of cases where the marketing campaign was a success (% of target variable with yes). Is this a balanced or imbalanced dataset?

7)	Perform descriptive and exploratory analytics

a)	Which educational group seems to have the highest proportion of clients subscribing to term deposit?

b)	Which job type seems to have the highest proportion of clients subscribing to term deposit?

c)	What about the effect of ‘poutcome’ (outcome of previous marketing campaign)? in predicting whether a client will subscribe to the term deposit

d)	Overall which variable or variables seem to have stronger relationship with the target variable?

e)	Are there any independent variables that are very strongly correlated with each other (multicollinearity problem)?

III.	Data Preparation

8)	Separate independent variables and target variables data into different datasets (X, and y)

9)	Some of the variables in the datasets are categorical as identified in Q.3. Convert the categorical variables into numeric values (Hint: use pd.get_dummies method for independent categorical variables in X)

IV.	Fitting an ML Model
10)	Start with any classification model and fit it on training data and then make predictions on the test data (the goal is to get good predictive accuracy on test data). Look at different metrics (accuracy, precision, recall, f1-score, and AUC scores).

V.	Optimize ML models

11)	Think as to what can be done to improve the model accuracy. Explore different options a) Scaling, b) Feature selection etc..

12)	Explore and investigate different ML models. This could include investigating different classification models (Logistic, Decision Trees, RF etc..)

13)	Tabulate and compare between different models.  Which model performed the best and what were the parameters, or strategies employed?

14)	Summarize your results and findings

15)	Investigate and explore techniques (oversampling, undersampling etc..) to deal with imbalanced datasets (OPTIONAL)










