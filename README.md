# Portfolio
Portfolio with a collection of my data science driven projects. 

- # Project 1: Titanic - Machine Learning from Disaster
**Objective:** use machine learning algorithms to create a model that predicts which passengers survived the Titanic shipwreck. In this project I used Logistic Regression, K-Nearest Neighbors and Decision Trees as the most basic models. Then I used some ensemble techniques such as Voting Classifiers, Random Forest, AdaBoosting and Gradient Boosting.

**The Challenge**: The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

The focus of this work is to build a predictive model that answers the question: “What sorts of people were more likely to survive?” using passenger data (i.e. name, age, gender, socio-economic class, etc).

**Data:**
 Two similar datasets from Kaggle that include passenger information like name, age, gender, socio-economic class, etc. One dataset is titled `train.csv` and the other is titled `test.csv`.

Train.csv contains the details of a subset of the passengers on board (891 to be exact) and importantly, will reveal whether they survived or not, also known as the “ground truth”.

The `test.csv` dataset contains similar information but does not disclose the “ground truth” for each passenger. 

Using the patterns found in the train.csv data, the goal is to predict whether the other 418 passengers on board (found in test.csv) survived.

- # Project 2: Data Science Field Analysis
**Objective:** As an individual I am really interested about Data Science. As a result of that interest I decided to do a study about the jobs related to the field of Data Science in the United States of America. My goal is to predict salaries of positions based on features related to the job using several machine learning regression models.  

**Data:**
In order to get the data required for this analysis I did some Web Scraping on the Glassdoor website using the Python library Beautiful Soup.
