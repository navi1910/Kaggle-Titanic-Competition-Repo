
# Kaggle Titanic Data Classification Project

## Titanic - Machine Learning from Disaster

<img src='https://github.com/navi1910/Kaggle-Titanic-Competition-Repo/blob/master/titanic-img.png' height=50% width=50%>

### Overview
The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

### Aim: 
To use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

## Data Dictionaty

| Variable | Definition                                                             | Key                       |
|:--------:|:----------------------------------------------------------------------:|:-------------------------:|
| survival | Survival                                                               | 0 = No, 1 = Yes           |
| pclass   | Ticket class                                                           | 1 = 1st, 2 = 2nd, 3 = 3rd |
| sex      | Sex	                                                                |                           |
| Age      | Age in years                                                           |                           |
| sibsp	   | Number of siblings / spouses aboard the Titanic                             |                           |	
| parch	   | Number of parents / children aboard the Titanic                             |                           |
| ticket   | Ticket number	                                                        |                           |
| fare     | Passenger fare	                                                        |                           |
| cabin	   | Cabin number	                                                        |                           |
| embarked | Port of Embarkation	|  C = Cherbourg, Q = Queenstown, S = Southampton                           |

## Methods 
* Data Preprocessing
* Machine Learning
* Supervised Learning - Classification
* Visualizations

<img src='https://github.com/navi1910/Kaggle-Titanic-Competition-Repo/blob/master/Age-hist.png' height=50% width=50%>

* Exploratory Data Analysis
* GridSearchCV and RandomizedSearchCV

## Technologies used
* Jupyter Notebook
* Python
    * Pandas 
    * Numpy
    * Matplotlib
    * Seaborn
    * Scikit-learn
    * Warnings
    * XGBoost

## Project Description
This is a competition dataset which is widely used by everybody who learns machine learning. The data was obtained from Kaggle. The aim is to use Machine Learning to classify whether passenger survived or not. 

<img src='https://github.com/navi1910/Kaggle-Titanic-Competition-Repo/blob/master/Age-hist.png' height=50% width=50%>

## Procedure
* Import the required Python modules.
* Load the the data as a Data-Frame.
* Check the basic information of the data.
* Null value treatment.

<img src='https://github.com/navi1910/Kaggle-Titanic-Competition-Repo/blob/master/Age-box.png' height=50% width=50%>

* Feature Engineering.
* Perform Exploratory Data Analysis using Data Visualizations.
* Convert the required Catergorical Variables to numeric variables.

### Model Building
* Separate the Independent and Dependent Variables.
* Assign variables to Train dataset and Test dataset.

* Models Built:
    * Logistic Regression
    * Decision Tree Classifier 
    * Random Forest Classifier
    * XGBClassifier
    * K Nearest Neighbors Classifier

Note: GridSearchCV and RandomSearchCV was used where ever required for tuning the models.

* The predictions were obtained from the test dataset.
* The predictions from the models were stored in different Data-frames and were converted into '.csv' format files for submission.
* The submitted '.csv' format files are available in the Repository.

## Results
Note: 'accuracy_metric' was the evaluation metric used by Kaggle.

* Logistic Regression                        - 0.76076
* Decision Tree Classifier                   - 0.77272
* Random Forest Classifier                   - 0.76315
* Random Forest Classifier with GridSearchCV - **0.78468**
* XGBClassifier                              - 0.74641
* XGBClassifier with GridSearchCV            - 0.76794
* K Nearest Neighbors Classifier             - 0.66507

### Best Result:
* Random Forest Classifier with GridSearchCV - **0.78468**
