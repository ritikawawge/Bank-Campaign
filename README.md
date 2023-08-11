# Bank-Campaign
The details of the input variables are as follows:

age (Age): Indicates th age of the person
job (Job): Indicates the profession of the person
marital (Marital Status): Indicates if the person is married.
education (Educational Level): Indicates the educational qualification of the person
default (Default status): Indicates if the person has credit in default.
balance (Balance): Indicates the bank balance
housing (Housing Loan Status): Indicates if the person has a housing loan
loan (Personal Loan Status): Indicates if the person has a personal loan
contact (Mode of contact): Indicates the mode of contact
day (Last contact day): Indicates the last contact day of the week
month (Last contact month): Indicates the last contact month of the year
duration (Last contact duration): Indicates the duration of the last contact in seconds
campaign (Number of contacts): Indicates the number of contacts performed during this campaign and for this client
pdays (Number of days that passed by after the client was last contacted from a previous campaign)
previous (Number of contacts performed before this campaign and for this client)
poutcome (Outcome of the previous marketing campaign)
The target variable is y.

The project has been divided into the following sections: 1. Preprocessing the data 2. Exploratory Data Analysis 3. Data Visualization 4. Machine Learning 5. Boosting Models 6. Conclusion and Recommendations


Accuarcy obtained from using different machine learning models include:

Logistic Regression: 88.7%
KNN : 87.63%
Decision Tree : 83.34%

Following this, XGBoost was used to boost the model performance. Final F1 score obtained from XGBoost was 0.94.
