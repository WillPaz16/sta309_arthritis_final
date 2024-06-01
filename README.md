# Arthritis Predictions Across Ohio
Predicting the prevalence of arthritis throughout Ohio.

## Dashboard

Create a dashboard that includes visualizations to investigate the relationship between arthritis and each of the following variables:

  * Gender
  * Age
  * Race
  * Daily drinks (i.e., alcohol use)
  * Smoking status
  * Physical activity
    
You must also include 2 additional exploratory plots. These can be anything relevant to the analysis, but here are some suggestions:

  * Relationship between any of the above variables and the different types of arthritis (“MCQ195”).
  * Relationships among any of the above variables, investigating possible sources of confounding.
  * Different types of physical activity and their relationships with arthritis risk.

-------------------------------------------------------------------------------------------------------------------------------

![arthritisDashboard](https://github.com/WillPaz16/sta309_arthritis_final/assets/144275029/f510d6c1-14dd-41c7-bd6f-38d2acf76f0b)

-------------------------------------------------------------------------------------------------------------------------------

## Modeling

You must train 5 different models to predict arthritis (since arthritis is categorical - yes/no - these should be classification models). You will use a 5-fold cross-validation to evaluate the models. Be sure to set a random seed each time you fit a model. Your choice of 5 models must meet the following criteria:

Models Chosen:
 * Random Forest Model (all predictors)
 * Random Forest Model (subset of predictors)
 * Logistic Regression
 * Classification Tree
 * Bagged Tree Model
 * k-Nearest Neighbors Model

-------------------------------------------------------------------------------------------------------------------------------

![image](https://github.com/WillPaz16/sta309_arthritis_final/assets/144275029/c97541c6-b302-4c89-8098-70a1a9e222a5)

-------------------------------------------------------------------------------------------------------------------------------

## County Map

Using the predictions from the logistic regression model, we created a chloropleth map that showcases the arthritis predictions across the counties of Ohio.

-------------------------------------------------------------------------------------------------------------------------------

![image](https://github.com/WillPaz16/sta309_arthritis_final/assets/144275029/1d1552fb-e324-4463-b2a5-1aae712bacc1)









