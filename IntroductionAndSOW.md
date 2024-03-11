# Statement of Work

## Introduction

Project to get insight into Amazon Fine Food Reviews to help the business to understand better their client’s needs, trends and predict satisfaction through sentiment analysis.

## Purpose and Objectives

-	Analyze the data looking for trends and how the clients feel about the products.
-	Additionally, develop a model to predict how customers will rate the products based on the reviews. Sentiment analysis will serve as an additional check of the quality of the data. The review and the score should match to avoid possible “troll” reviews. It can be used to possibly filter future data in the trend’s analysis or as an additional metric for business metrics such as client satisfaction.

## Data sources and tools

To develop this project, we will be using:
-	The amazon_fine_food_reviews dataset provided by the client. NLP will be required, since an important part of the data is raw text. 
-	Python and jupyter notebook environment for the data analysis and model development. The model will use sentiment analysis techniques.
-	Azure ML for the deployment.
Tasks
-	Data Cleaning: search for inherent problems in the data. Inconsistencies, duplicated data, spurious outliers, missing values and errors.
-	Data Analysis: reporting of the direct insights found in the data, such as trends and client likeness.
-	Data processing: search for new features, processing the text and processing numeric data.
-	Sentiment Analysis model: try different models along with different data processing and different features. 
-	Comparing the results between the different models and benchmarking them with external sentiment models.
-	Model deployment: pipeline and endpoint to predict the sentiment of new data
-	Analysis of the sentiment results

## Milestones

- Monday 3/4/2024: define the Statement of Work, perform data exploration to get insights on the dataset, perform data cleaning, define functions for some basic data and text processing. If there is time build a simple model (Naive Bayes?) to use as benchmarking for the next phases.

  - Tuesday 3/5/2024: compare different models with different hyperparameters and decide which text vectorizer (CountVectorizer or TFDIF) to use. Try using 2-grams / 3-grams.  Decide how to handle the imbalance in the dataset. start the model deployment and pipeline in ML studio.
  - Wednesday 3/6/2024: If not already done perform hyperparameter tuning. Decide what we want to plot. Fix eventual bugs and deploy the model.
  - Thursday 3/7/2024:  draw conclusions and prepare the presentation

  - Friday 3/8/2024: present our work to the class

## Deliverables
-	Data cleaning pipeline for production and trained model in azure ML
-	Report of the Project with the data analysis and the model development process
-	Final Presentation


# Notebooks order:

1. DataCleaning
2. DataPreprocessing
3. DataExploration
4. Word2VecTraining
5. ComparingPretrainingModels
6. ModelTraining
7. TrainingDeployment

Independently: SentimentAnalysis
