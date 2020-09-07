Big Data Tools and Analysis Project : Ted Talks
Project Team:
Nadeem Masani : 824660441
Piyush Kurkure : 823708438

Purpose and a brief description: 
This project uses Ted Talks Data set from Kaggle.com which contains data(metadata and Transcripts) for 2550 ted talks held by the company up to September 2017

Link to download the data set: https://www.kaggle.com/rounakbanik/ted-talks/download

Google Drive Link: https://drive.google.com/uc?id=19YqIehG5BJB0gYmAZ9I9QbIQgUfnlHOA&export=download


This project is divided into 3 parts.
1. Data Analysis and Visualizations: This aims to provide answers and visualization to questions like 
        i)What are the most popular ted talks?
        ii)How are views and comments on ted talks distributed? Is there any correlation between them?
        iii)What kind(theme) of ted talks attract the maximum discussion and debate (in the form of comments and views)?
        iv)Which months/days are most popular among TED and TEDx chapters?
        v)How are ted talks rated and finding out which ted talks have the best ratings?
   
    Data Analysis is done using pyspark and visualizations uses pandas,matplotlib and seaborn.
                
2. Text-based Content Recommender: This aims to provide a content recommendation of ted talks based only on the text transcripts of the ted talks, this is helpful to provide recommendation for new users whose recommendations maybe cannot be made due to no past user activity.

3. Prediction model to predict if a ted talk will be popular or not. The popularity of the TED talk will be defined by the type of Ratings whether the show had positive feedback or negative feedback. The aim is to build a classifier based on the tags associated with the ted talk and occupation of the speaker to predict whether the talk will be popular or not.

The Jupyter notebook takes around 8-10 minutes to run