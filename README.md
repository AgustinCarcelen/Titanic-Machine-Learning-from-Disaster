# Titanic-Machine-Learning-from-Disaster
case study, predict titanic survivors

## Description
This is the legendary Titanic ML competition. We will use machine learning to create a model that predicts which passengers survived the Titanic shipwreck. For this we will use the database provided by kaggle: [Data](https://www.kaggle.com/c/titanic/data)<br/>

## EDA
You can see the code for these steps [here](https://github.com/AgustinCarcelen/Titanic-Machine-Learning-from-Disaster/blob/8084ebb03428010c5a9d72dcac0365555f1b136a/Titanic.ipynb)<BR>
1. We import the database<BR>
2. We look for duplicates<BR>
3. We eliminate the columns that do not influence our study<BR>
4. We fix the age column, fill in the null values and put the proper format<BR>
5. We modify the sex column to adapt it to 1 and 0 <BR>
6. Once we have the database ready, we graph the numerical variables to see possible anomalies and better understand the resulting database<BR>
7. We separated our database to select our target, to know who will survive<BR>
8. Now we make a correlation matrix to know if there is a relationship between the selected columns<BR>
9. At this point, we are ready to train our model<BR>

## Conclusions
The original database had irrelevant columns for our case study, such as: PassengerId, Name, Ticket, Embarked and Fare. On the other hand, the Cabin column contained 80% of the empty data, with which we have also discarded it. <BR>

Regarding the age column, 25% of the data had a null value. After calculating the median age and seeing that it was an acceptable value for our study, we have filled in the null values with it.<BR>

Another problem with this column was that it contained the data saved in fractions, so we only took into account the age already fulfilled.<BR>

Lastly, we have changed the male and female gender column values to 1 and 0, to work better with our training model.<BR>

Once we have the database prepared, we have made graphs to better understand our resulting database and we have checked its correlation.<BR>

With all this we can say that the characteristics that seem to have the greatest impact on the survival rate are: <BR>
1. Pclass: The place where they traveled. 1st, 2nd, 3rd<BR>
2. Sex: Male or female<BR>
3. Age: Age of the person<BR>
4. SibSp: Family relations of siblings / spouses aboard the Titanic<BR>
5. Parch: Family relations of parents / children aboard the Titanic<BR>

## Random sample [Data](https://www.kaggle.com/ash316/eda-to-prediction-dietanic)<br/>

  First of all, he analyzes each variable separately, performing calculations and graphs to better understand everything he can extract from the database.

He then separates the columns into categories and analyzes them separately. He uses relations with the rest of the columns to fill in the columns that have null values.

He looks for correlation between the columns and discards those that are not necessary for the study.

  
  
  
  
  
  
  
  
  



