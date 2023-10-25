# Titanic Survival Prediction using PySpark

## Project Overview
This project aims to predict the survival of passengers on the Titanic using machine learning. The dataset used for this project is the famous Titanic dataset available on Kaggle. The project demonstrates data exploration, data cleaning, feature engineering, and building machine learning models using PySpark

## Dataset
The dataset consists of the following fields:

- PassengerId: The ID given to each traveler on the boat.
- Pclass: The class of the ticket the passenger purchased (1st, 2nd, or 3rd).
- Name: The name of the passenger.
- Sex: The gender of the passenger.
- Age: The age of the passenger.
- SibSp: The number of siblings or spouses the passenger had aboard the Titanic.
- Parch: The number of parents or children the passenger had aboard the Titanic.
- Ticket: The ticket number.
- Fare: The amount of money paid for the ticket.
- Cabin: Cabin number where the passenger stayed.
- Embarked: Where the passenger boarded the Titanic. C represents Cherbourg; Q represents Queenstown; S represents Southampton.

## Tools and Libraries
- PySpark
- Matplotlib
- Seaborn
- Jupyter Notebook


## Steps Involved
1. Data Loading and Exploration:

- Load the data using PySpark.
Explore the data to understand the distributions and relationships between variables.
Data Cleaning and Feature Engineering:

- Handle missing values.
Create new features like FamilySize from existing features.
Convert categorical features into numerical values.
2. Data Analysis:

- Analyze the correlation between various features and the target variable.
- Visualize the relationships between features and the target variable.
3. Modeling:

Split the data into training and testing sets.
- Build and train machine learning models:
1. Logistic Regression
2. Random Forest
3. Gradient Boosted Trees
- Evaluate models using the Area Under the Curve (AUC) metric.
- Perform hyperparameter tuning to improve model performance.

## Results
The Gradient Boosted Trees model achieved the highest AUC score of approximately 0.763, indicating a good level of predictive accuracy. Further tuning and exploration of other advanced models or ensemble techniques may lead to even better performance.

## Future Work
- Experiment with more advanced models and ensemble techniques.
- Explore further feature engineering possibilities.
- Investigate misclassifications to understand where the model can be improved.
- Consider setting up a simple web application to demonstrate the model in action.
## Acknowledgements
Dataset source: Kaggle Titanic Dataset
link: https://www.kaggle.com/datasets/vinicius150987/titanic3
