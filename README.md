# Medical No Shows

##### For this project I wanted to do some sort of prediction test based on at least 10 feature variables on a dataset with over 100,000 entries. I saw quite a few on predicting diabetes or heart diesease, but not as many concerning missing appointments. There were a lot of interesting findings after analyzing the data that you can see from my project as well as the presentation. I have attached a link to the presentation in the README.

### The Process
##### About The Data
* from 2016
* based in Brazil
* 14 columns and 110527 rows
##### Loading Libraries And Data
* raw data from kaggle
* dataframe created from csv file
##### Data Cleaning
* Make sure format of data is correct (int, float, object)
* Rename columns
* Change ScheduledDay and AppointmentDay to Datetime
* Get difference between ScheduledDay and AppointmentDay
* Remove values with Age < 0
* Get dummy variables
* Check for null values
##### Dava Visualization
In this section I am going to do create some graphs, charts and look at correlation patterns within the data. Since the main goal is to predict Show/No Show, everything will be related to that. Some keys factors that I will be looking at include:
* Gender
* DaysInAdvance
* Age
* Neighborhood
* SMSreceived
* AppointmentDay_DOW
* Scholarship
##### Data Modeling
Here I am going to run a variety of classification analyses to determine which tecnique is best for predicting the outcome (Show/NoShow).

After doing data exploration, I have determined that some of the features are not necessary
* Alcoholism
* Handicap
* Diabetes

One Hot Encoding, Decision Tree, SVM, Random Forest, Gradient Boosting
#### Tech:  Python, Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn

Project link https://docs.google.com/presentation/d/1CZAWutiHRBP0aePEBD1AiK3wBufbimEo9g2dM3TEMD4/edit?usp=sharing
