# corruption_and_happiness

### Brief Overview
This is a machine learning project that explores corruption as a predictor of happiness. The project was completed over the summer of '23 under the guidance of BreakThrough Tech AI, a machine learning fellowship run by Cornell Tech.
The data used is the 2018 world happiness report obtained from https://worldhappiness.report

### Motivation
As a Kenyan native, born and raised, topics around the well-being of my country have always been near and dear to my heart. Currently, corruption within the Kenyan government is causing a lot of political instability. As such, there has been an influx in the number of people on different social media platforms airing their grievances about the current state of government. This observation was the motivation behind this project. 

### Goal
The goal of the project was to evalate if corruption can be used as a predictor of happiness granted that it seems intuitive that the higher the corruption in a country the less happy people would be. 

### Approach
For the project, happiness is the label while corruption is the feature value. As per the dataset, corruption was measured on a scale of 0 - 1 where values closer to 0 indicate low perceptions of corruption and values closer to 1 indicate high perceptions of corruption. The key steps used to implement the project plan include:

1. Loading the data set and save it to a Pandas DataFrame.
2. Data wrangling
3. Designing models and choosing the best one

### Resultus
Here, 4 models were built--Linear, Decision Tree, Random Forest, and Gradient Boost Decision Dree models. The Random Forest Model emerged as the best model with a `r2_score` of 0.8786, a `rmse` value of 0.3750, and a 84.24% accuracy in predicting corruption as a measure of happiness across different countries between the years 2012-2017. 