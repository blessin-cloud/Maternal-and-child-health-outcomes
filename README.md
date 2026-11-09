# Maternal and child health outcomes analysis
### Table of Content
 -  [Project overview](project-overview)
 -  [Data source](data-source)
 -  [Tools](tools)
 -  [Data cleaning and preparation](data-cleaning-and-preparation)
 -  [Exploratory data analysis](exploratory-data-analysis)
 -  [Data analysis](data-analysis)
 -  [Results](results)
 -  [Recommendations](recommendations)
 -  [References](refrences)

### Project Overview
 To have a better understanding on how maternal demographics,pregnacy-related health conditions,antenatal care utilization and delivery characteristics are associated with newborn birhth outcomes.

### Data Source
The primary dataset used for this analysis is the 'train.csv' file in prediction interval competition :Birth Weihght from kaggle-cdc natality records(2007-2002).
### Tools
 - Excel - Data cleaning
    - [download here](https://wwww.kaggle.com/competitions/prediction-interval-competition-i-birth-weight/data)
 - Power Bi - Data Visualization and Creating Reports
### Data Cleaning And Preparation
In the initial data preparation phase I did the following:
1. Data loading and inspection
2. Handle missing Values
3. Check for duplicates
### Exploratory Data Analysis

1. understand demographic patterns and their relationship with newborn birth outcomes
2. evaluate antenatal healthcare utilization and prenatal care patterns
3. identify maternal health characteristics associated with differences in newborn birth weight
4. examine delivery patterns and their relationship with newborn outcomes
### Data Analysis

  some basic dax measures
    
             ---
               power bi
               total birth record=countrows('train')
                maternal bmi category= switch(true(),train[bmi]<25,"very low",train[bmi]<50,"low",train[bmi]<75,"moderate","high")
              ---
### Results
1. the newborn weight is normal (2500-3500)g with the highest record of 63,000cases
2. vaginal delivery is the most used method with 71,390 cases
3. women above 30 years have the highest record of deliverieseco(51,000 cases)
4. women with prenatal care initiation(less than 4 weeks) have the highest record of 83,000cases
5. women with low weight gain(25-49) have the highest record of 56,000 cases
6. wonmen with low bmi(25-49) have the highest record of 57,000 cases
### Recommendation
1. management can improve on prenatal care routines
2. management can work on awareness on maternity guidelines on weight gain and body mass index.
### Refrences
 kaggle
 
